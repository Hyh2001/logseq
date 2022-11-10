# 查看GPU状态
	import torch
	from torch import nn

	# to see whether GPU is available
	print(torch.cuda.is_available())  

	# how many GPUs are available
	print(torch.cuda.device_count())

	# soure GPU
	torch.cuda.current_device()


	# get the name of GPUs
	torch.cuda.get_device_name(0)

# Tensor在GPU上计算
## 原理 
创建一个Device并把可用的GPU放进去，然后用这个device存储用于训练的数据
## 单块GPU
	# 创建GPU对象
	device = torch.device("cuda:0" if torch.cuda.is_available() else "cpu")

	# 训练数据
	features = features.to(device)
	labels = labels.to(device)

	# 模型数据
	net.to(device)
