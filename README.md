# ProDecoder2.0

## 单文件输入
自己设计了三种格式的报文，input.txt这一个文件夹作为输入，txt中的每一行即为一条报文数据  
module1, module2&3, module4分别是四个模块的代码和运行结果  
cluster1, cluster2和cluster三个txt文件分别是三个簇的聚类结果  
test1, test2和test3三个txt文件分别是三种类别的测试数据  
precision&recall.ipynb是测试代码以及结果  

## 真实协议输入
与单文件输入不同，此处每一条报文都是一个单独的txt文件，因此总的输入是一个input文件夹  
共使用了三种不同的协议，分别是HTTP, SMTP和QQ
