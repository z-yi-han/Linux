## 指令
#### 1.grep
从文件中找出包含指定内容的那一行  
grep “xxx”  文件名
-n:把行号带上  
-v:没有匹配成功的才要  
-i:忽略大小写
#### 2.zip&unzip
打包和压缩 
zip -r srcdir.zip  
unzip srcdir.zip  
指定路径解压:unzip srcidr.zip -d/xxxx  
#### 3.rz&sz
Win和Linux互传压缩包
#### 4.tar  
- czf:创建压缩包
- xzf:解压 + -C/xxx选项解压到指定目录
#### 5.scp
远程拷贝:scp dst.tgz  用户名@公网IP 路径
#### 6.bc
在Linux中简单的计算器(用的少)
#### 7.uname 
-a:查看全部系统信息
-r:查看内核版本
-s:查看内核名称
## 知识点
- 打包:文件合并 压缩:减少体积
-  打包防止文件丢失,压缩减少体积，节省空间，网络传送有效减少传送时间
- ctrl c:中止前台任务
- Tab:命令补全，档案补齐
- ctrl r:搜索历史命令
- ctrl d:退出命令行(退出当前用户)
- Linux会记录历史命令
- Linux中云服务器永不关机
- Linux没有开机指令