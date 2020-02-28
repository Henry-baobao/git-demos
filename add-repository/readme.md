<!--
 * @Description: 
 * @Version: 
 * @Author: Henry
 * @Date: 2020-02-24 12:02:28
 * @LastEditors: Henry
 * @LastEditTime: 2020-02-24 12:39:50
 -->
### 创建版本库
git init

### 添加文件到Stage
//添加所有文件到暂存区
git add **.**
//添加指定文件
git add readme.md

### 提交到Repository
//-m 后面输入提交说明，方便从提交历史找出改动记录
//从暂存区中把内容提交至当前分支
git commit -m "commit readme.md file"

### 查看
//掌握工作区状态
git status

//查看改动内容
git diff readme.md

### 版本回退
//查看提交历史
git log --pretty=oneline

//版本回退(commitID:git log查到的commit id)
git reset --hard commitID

//查看命令历史
git reflog

### 工作区和暂存区
//当前文件夹为工作区
//.git文件夹为Git版本库（Repository）
//Git的版本库里存了很多东西，其中最重要的就是称为stage（或者叫index）的暂存区，还有Git为我们自动创建的第一个分支master，以及指向master的一个指针叫HEAD。
![](./imgs/repository.jpg)