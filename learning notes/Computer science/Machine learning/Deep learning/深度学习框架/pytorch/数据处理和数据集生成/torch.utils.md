- ---
  
  ---
  torch.utils data
  ```python
  	import torch
  	from torch.utils import data
  	DataSet = data.TennsorDataset(*data_arrays)   # data_arrays 是数据和标签构成的列表 (features,labels)
  	data.DataLoader(DataSet,batch_size,shuffle = ,num_workers = ) # 用于批量导入数据，shuffle = True 表示打乱顺序,num_workers 表示用于加载的进程数量
  ```
-