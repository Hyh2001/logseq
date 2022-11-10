# 加载和保存向量
	torch.save(x,’file name’)
	A = torch.load(‘file name’)
## 存储张量列表
	torch.save([x,y],’file name’)
## 存储字典
	torch.save(dict,’file name’)

# 加载和保存模型
	torch.save(net.state_dict(),’file name.params’).   #模型中的所有参数存成一个字典
## 加载模型
	Clone = net()
	Clone.load_state_dict(torch.load(‘file name.Paramus’))