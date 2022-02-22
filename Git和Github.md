# Git

### 一、Git概述
&ensp; &ensp; Git是一个免费的、开源的**分布式版本控制系统**，可以快速高效地处理从小型到大型的各种项目。

https://git-scm.com/



### 二、何为版本控制
&ensp; &ensp; 版本控制是一种记录文件内容变化，以便将来查阅特定版本修订情况的系统。
&ensp; &ensp; 版本控制其实最重要的是可以记录文件修改历史记录，从而让用户能够查看历史版本，方便版本切换。



### 三、代码托管中心
代码托管中心是基于网络服务器的远程代码仓库，一般我们简单称为远程库。
- **局域网**
	
	​    GitLab
	
- **互联网**
	    Github
	    Gitee



四、Git基本命令

1. git config -- global user.name 用户名
> 配置用户名

2. git config --global user.email 邮箱
> 配置邮箱

3. git init
> 初始化本地库

4. git status
> 查看本地库状态

5. git add 文件名
> 把本地的文件添加到暂存区

6. git rm --cached 文件名
> 删除暂存区的文件

7. git commit -m "日志信息" 文件名
> 提交本地库，并添加日志信息（默认需要的）

8. git reflog
> 查看引用日志信息

9. git log
> 查看详细日志信息

10. git reset --hard 版本号
> 版本切换

## 远程连接Github
https://github.com/ssssbbbbb/Study_the_warehouse.git  
**方法一：**
1. 先查看当前是否有链接
> git remote -v
2. 创建连接
> git remote add ori https://github.com/ssssbbbbb/Study_the_warehouse.git
> 创建连接后，可以查看是否连接成功，例：
> $ git remote -v
> ori     https://github.com/ssssbbbbb/Study_the_warehouse.git (fetch)
> ori     https://github.com/ssssbbbbb/Study_the_warehouse.git (push)
> 一个推送，一个拉取
  
**方法二:**(反正是在GitHub上面复制粘贴的)
```
git remote add origin https://github.com/ssssbbbbb/Study_the_warehouse.git
git branch -M main
git push -u origin main
```


