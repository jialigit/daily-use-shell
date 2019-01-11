###Linux commands must know for developers

运维开发人员日常最常用的linux 命令集合。

1.文件操作都有哪些命令？
  1.1 创建文件，文件夹
  创建文件：touch <filename>
  创建文件夹： mkdir <dirname>
  1.2 查看，修改文件权限信息
  查看：ls -l/ll
  修改权限： chmod <...>
  1.3 查看，修改文件所属用户，用户组信息
  修改所属：chown <...>
  1.4 查看，编辑文本文件内容
  cat/tail/head
  编辑器：vi/vim
  
  另外：vi操作命令参考---》待补充
  1.5 文件移动，拷贝
  移动：mv
  拷贝：cp
  远程拷贝：scp
  1.6 打包/解包，压缩
  打包：tar
  解包：untar
  压缩：zip
  解压缩：unzip
 
  
2.用户管理
2.1 添加，修改，删除用户有哪些命令？
 添加用户： adduser/useradd <username>
 修改用户密码：passwd <username>
  
  
3.管理
##文件文本相关

3.1 根据文件名，类型等查找文件
find 

3.2 从文件中查找符合给定的通配符的内容
grep 

3.3管道、重定向
格式： 命令1 | 命令2， 表示前面命令的输出是后面命令的输入 
3.4 awk -F FS

3.5 排序
sort/unique/cut/wc

4 系统管理
4.1 查看系统运行情况 
top：
ps：
free：

4.2 查看网络端口占用情况
netstat
 
4.3 查看磁盘占用情况
du -f/df -h

5 shell脚本
1.特殊变量/变量命名规范

2.流程控制

3.函数


