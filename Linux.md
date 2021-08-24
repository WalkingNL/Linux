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

* `users`, `who`, `w`三个命令，都是用来展示登陆到当前终端的用户及其他相应的信息。其中，命令`users`仅现实用户名，`who`及`w`展示的信息更为详尽。

* `finger [用户名]`命令用来调查用户。

* `at`, `atq`, `atrm`, `at`命令可以在指定时刻，执行一次任务，`atq`命令可以查看当前任务列表中，哪个任务要被执行，`atrm`可以删除任务列表中，要被执行的任务。

* `cron` 可以周期性的执行指定任务


