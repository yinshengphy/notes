# hdfs常用java api

- **读写操作**  
操作`hdfs`分布式文件系统的类为`FileSystem`对象  
创建文件夹（递归创建）：`fs. mkdirs()`  
写文件:`fs.create（new Path()）`，返回`FSDataOutputStream`对象  
读文件:`fs.open(new Path())`  , 返回`FSDataInputStream`对象  

