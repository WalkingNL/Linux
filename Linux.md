#### Basic commands

* mkdir -p [file]
* ln -s [source] [dest]
* wget -c [source link]

---
* `man -f 具体命令`
    
      如 man -f ls ; 用来查找命令ls存在于哪些man文件中
      
* `info 具体命令`，info是一个基于菜单的超文本系统。包含少许关于Linux shell、工具、命令的说明文档。如：

    info ls
列处命令ls的相关说明信息

* `ls -l -n [文件]`。经常用到命令`ls -l`，却很少使用选项-n，加上这个选项的含义是显示 UID及GroupID所对应的具体数字

* `id`及`groups`，这两个命令分别是用来查看当前用户的UID，以及查看所属的组

* `passwd`命令用以修改密码
  
    passwd user01
 用来修改user01用户的密码

