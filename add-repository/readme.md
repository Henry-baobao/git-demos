<!--
 * @Description: 
 * @Version: 
 * @Author: Henry
 * @Date: 2020-02-24 12:02:28
 * @LastEditors: Henry
 * @LastEditTime: 2020-02-24 12:15:54
 -->
### 创建版本库
git init

### 添加文件到Repository
//添加所有文件
git add **.**
//添加指定文件
git add readme.md

### 提交到Repository
//-m 后面输入提交说明，方便从提交历史找出改动记录
git commit -m "commit readme.md file"

### 查看
//掌握工作区状态
git status

//查看改动内容
git diff readme.md

### 版本回退
//查看log
git log