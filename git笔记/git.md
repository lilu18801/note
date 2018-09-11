1. git全局指定用户名、密码
----------
	git config --global user.name author #将用户名设为author
	git config --global user.email author@corpmail.com #将用户邮箱设为author@corpmail.com
	git config --list  检查配置信息

	ssh-keygen  生成公钥


2. git使用
----------
	初始化仓库:
			git init
	添加文件，跟踪文件:
			git add 文件
	提交:
			git commit  提交至本地仓库

	比较：
			git diff staged 

	删除文件:
			git rm
		 
	


