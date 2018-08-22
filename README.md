> 学习自RobbieHan的[知乎专栏SandBox](https://zhuanlan.zhihu.com/sandbox)

# 0 配置环境

* pip install virturalenvwrapper-win

* mkvirtualenv -p "D:\Anaconda3\python.exe" sandbox-env

* 系统自动激活虚拟环境

* 关闭虚拟环境: deactivate

* 列出所有虚拟环境: workon

* 激活某虚拟环境: workon xxx

# 安装mysql

* 在mysql文件夹目录下配置 my.ini

* 以管理员身份输入安装命令 mysqld install

* 启动mysql服务 net start mysql (在5.7需要初始化data目录 mysqld --initialize-insecure)

* 修改默认的密码: set password for 'username'@'host' = password('newpassword')