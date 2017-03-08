# git的使用
## 1  初始化一个git仓库 
> ##`git int`	

## 2  配置用户名和邮箱
>##`git config user.name 'name'`
>##`git config user.email '123@qq.com'`

## 3  查看配置信息
>##`git config --list`

## 4  查看状态
>##`git status`

## 5  添加指定文件（添加到缓存区）
>##`git add '文件路径'`

## 6  将文件提交到仓库
>##`git commit -m '提交信息描述'`

## 7  修改文件
>##重复第五六步


## 8 将文件从暂存区放到仓库（repository）中
>##`git commit -m '提交信息描述'`


## 9 查看提交信息
>##`git log`
>## `git log --oneline`

## 10 查看提交信息
>##`git log`

## 11 分支
### 在本地创建新分支
>## `git baranch newbarnch`
###切换到新的分支
>## `git checkout newbarnch`
###将新分支推送到github
>##`git push origin newbaranch`
###在本地删除一个分支
>##`git barnch -d newbaranch`
>###在github远程端删除一个分支
>##`git push origin :newbranch`(分支名前的冒号代表删除)

