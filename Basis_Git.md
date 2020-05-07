# the basis of Git & GitHub
> this is not completed

***
### 本地Git命令
***
#### 1. 把当前目录变成Git可以管理的.
	git init
#### 2. 添加文件
##### I. 添加单个文件
	git add < file >
##### II. 添加全部文件
	git add -A
#### 3. 提交修改
	git commit -m < message >
#### 4. 查看状态
	git status
#### 5. 查看提交历史
	git log
#### 6. 版本回退
	git git reset --hard < commit_id >
##### 注意
	HEAD 表示当前
	HEAD^ 表示上次提交(^表示上次)
	git reflog 查看命令历史，可用于返回未来
#### 7. 撤销修改
##### I. 未使用 add
	git checkout -- < file >
##### II. 已使用add，未使用commit
	git reset HEAD < file >
	重复 I
##### III. 已使用commit，未提交到远程
	参看 6.
#### 8. 删除文件
	git rm
***
### GitHub命令
***
#### 1. 关联远程库
	git remote add origin git@github.com: < name >/< repository  >.git
#### 2. 推送分支
##### I. 第一次推送
	git push -u origin <  branch-name >
##### II. 普通推送
	git push origin <  branch-name >
#### 3. 克隆远程库到本地
	git clone git@github.com:< name> /< repository >.git
***
