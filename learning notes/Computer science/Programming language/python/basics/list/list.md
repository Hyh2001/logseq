#  
## 表示
	[a,b,c,d]
## 类型转换
	list(A)
## 元素访问
### slicing
	A[n1,n2]
## 元素操作
### 修改元素
	A[a] = number
### 添加元素
#### append
	A.append(x)
在末尾添加x
#### insert
	A.insert(number,x)
在number处插入x
### 删除元素
 #### del
	del A[n]
#### pop
	 x = pop(A)  #弹出列表末尾元素
	 pop(number)  #弹出任意位置变量
#### remove
	 x = remove(' ') #删除指定值
### 排序
	A.sort(reverse = True) #按字母顺序排列，reverse参数为真则顺序相反
	B = sorted(A)  #A的顺序不变
	A.reverse()  #倒转顺序
## 列表操作
### 获取长度
	len(A) # 获取列表长度
### 遍历
	for n in A:
###  创建数值列表
#### 1
	range(n1,n2,step)
#### 解析式
	A = [i for i ]  #i符合的公式
### 复制




