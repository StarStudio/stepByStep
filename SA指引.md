# 星辰 2016 SA 养成指引       
> author:joker、starduster
        

  
了解 Unix,Linux 操作系统 和计算机网络基础 
-         
**目标：**

1. 我们为什么要使用 Unix/Linux
2. 了解 Unix/Linux 基本结构
3. 了解我们的互联网的基本结构，尤其是分层模型，这对我们管理服务器至关重要
 
**参考资料**        

1. [维基百科](https://zh.wikipedia.org/wiki/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F)      
2. [操作系统原理及应用](http://c.biancheng.net/cpp/u/xitong/)
3. [如何成为一名黑客](http://translations.readthedocs.io/en/latest/hacker_howto.html)（这篇文章告诉你我们为什么要使用 Unix 系统）
4. 
5. 《图解 TCP/IP》
6. 任意版本的《计算机网络》

Linux 系统安装   
-   
	
**目标:**	
		
1. 熟悉常用linux系统的安装      

**测试方向:**
	
1. Virtual Box 安装CentOS/Debian(Desktop/Server)
2. 尝试安装 Gentoo、Arch 等没有自带安装引导的发行版（可选）
		
**时长: 1~2周**      
**参考资料:**

1. 谷歌
2. [Archwiki](https://wiki.archlinux.org/)

包管理器及常用命令  	 
-
**目标:**	
    
1. `ls`,`mv`,`useradd`,`usermod` 等命令       
2. `vim`,`nano`,`emacs` 编辑器   
3. Linux 权限       
4. CentOS/Debian 系的 `yum`/`apt` 包管理器 
    	
**测试方向:**
      
1. 了解更新源原理,熟悉管理器的常用操作,如`apt-cache search`，了解什么是依赖，怎么处理依赖关系，了解`yum`和`apt-get`使用上的一些区别   
2. 文件/用户权限管理

**时长: 2~4周**     
**参考资料:**
	
1. 《鸟哥的私房菜(基础篇)》
2. man手册
		
环境搭建  
-    
**目标:**
	
1. Apache/Nginx
2. PHP/Python 后端服务 
3. MySQL
     	
**测试方向:**
	
1. LNMP/LAMP 环境搭建（重点了解配置文件格式）
2. MySQL数据库安装配置及基本操作
3. PHP 和  Apache/Nginx 如何交互（fastcgi、uwsgi、mod_php）
	
**时长: 4周**      
**参考资料:**
	
1. 《鸟哥的私房菜(服务器篇)》
2. 《深入理解 Nginx》
3. 《MySQL 必知必会》
4. 官方文档：nginx.org，中文翻译：[淘宝 tengine 项目文档翻译](http://tengine.taobao.org/nginx_docs/cn/)

Shell 脚本编程和 Linux 环境进阶
-      
**目标:**
	
1. Shell 脚本入门
2. crontab 及进程机制
3. 学习如何管理服务器	     

**测试方向:**
	
1. 了解 bash 的基本语法和一些保留字如反引号<code>`</code>、中括号<code>[</code>等
2. 使用管道(`|`)和重定向(`>`、`>>`)传递参数和信息，使用`find`、`grep`、`xargs`进行信息处理
2. 分支判断和条件、循环的语法 
3. 使用`awk`和`sed`输入输出流和文本处理
4. 使用`netstat`等判断服务器网络状态、使用`ps``top`进行进程管理，
5. 使用`iptables`对网络进行基本管理
6. 使用`cron`定时任务处理
	
	
**时长: 4~6周**       
**参考资料:**
	
1. 《高级 Bash 脚本编程指南》
2. 《Linux 命令行与 Shell 脚本编程大全》
3. [极客学院 Wiki](http://wiki.jikexueyuan.com/project/shell-tutorial/shell-brief-introduction.html)
4. [Linux 工具快速教程](http://linuxtools-rst.readthedocs.org/zh_CN/latest/index.html)

Python 入门
- 
**目标:**
	
1. Python 基础语法
2. Python 常见库的使用
3. 开发(爬虫,数据处理,后台开发,CUDA等方向)

**测试方向:**
      
1. Python 实现 Linux 服务监控及数据存取
2. 开发方向任选,成品展示

**时长: 3~6周**       
**参考资料:**
	
1. 《Python cookbook》,python 标准库
2. 官方手册
3. [廖雪峰的网站](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
4. [深入 Python3](http://www.ttlsa.com/docs/dive-into-python3/)

What's more?
-
实际上我是想把标题写成入门指南的，实际上写的并不只是入门的内容，关键在于动手去做，走过上面这些，可能已经半年、一年或者更长时间过去，接下来有什么发展方向，相信到时候自己自有体会，在这里列出一些可以参考的方向：

* Nginx 高级应用（负载均衡、反向代理），了解 HAProxy、Squid 等工具—— Web 方向
* 深入了解数据库结构—— DBA（数据库管理员）方向
* 了解 KVM OpenVZ Docker —— 虚拟化方向
* ······

如果你想作为一个 SA 走出校园，这些网站可能帮得到你：

* [UC 技术博客](http://tech.uc.cn)
* [百度运维组博客](http://op.baidu.com)
* [小米运维组博客](http://noops.me)

Happy coding~
