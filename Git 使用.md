# Git 使用
分布式的代码仓库，包括本地仓库和远程仓库，每个人本地都会有一个仓库，如果需要让别人看到，需要push到远程仓库

## 概念
* 仓库(Respository), 存放代码变更的地方
* 提交(Commit), 把代码变更记录存放到仓库里
* 日志(Log), 记录历史
* 状态(Status), 当前工作取文件的新增、修改、删除等
* 工作区
* 暂存区, 可以把一些提交暂时保存起来
* 本地仓库
* 远程仓库


## 流程
* 在github上创建git仓库
* clone到本地

	```
	git clone github.com/xxxx.git
	```
* 在本地工作取修改（Add、Update、Delete）
* 添加到暂存区
	
	```
	git add -A
	```
* 提交到本地仓库

	```
	git commit -m"fix: a good description of this bug"
	```
* push到远程仓库

	```
	git push
	```