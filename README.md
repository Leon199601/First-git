# First-git

1、首先在github官网新建个文件夹

2、#将云端的文件夹克隆到本地

​	git clone https://github.com/Leon199601/First-git.git

3、初次链接

​	cd

​	#初始化一个git仓库

​	git init

​	git commit -m “备注”

​	git branch -M main

​	#添加github远端	

​	git remote add origin https://github.com/Leon199601/First-git.git

​	#推送到github的main

​	git push -u origin main

4、更改文件，eg：更改readme文件

​	cd

​	git init

​	#添加文件到git仓库

​	git add *

​	#时刻掌握工作区的当前状态

​	git status

​	#查看修改内容

​	git diff

​	#按q退出

- 要明白这3个概念，工作区（**working tree**），暂存区（**index /stage**），本地仓库（**repository**）
- git跟不同的参数，比较不同的区间的版本。

1. git diff：是查看working tree与index的差别的。
2. git diff --cached：是查看index与repository的差别的。
3. git diff HEAD：是查看working tree和repository的差别的。其中：HEAD代表的是最近的一次commit的信息。

 **综上所述：git diff 后面跟文件名称是是查看工作区（\**working tree\**）与暂存区（\**index\**）的差别的。**

​	git commit -m "备注"

​	git push

