<!--
 * @Description: 
 * @Version: 
 * @Author: Henry
 * @Date: 2020-02-24 10:38:40
 * @LastEditors: Henry
 * @LastEditTime: 2020-02-28 13:45:17
 -->
 VSCode中git应用
 ==============

## 上传本地仓库至GitHub
### 创建Repository

+ git init
![git-init img](https://img-blog.csdnimg.cn/20190227221940837.png)

### 保存至暂存区

+ git add
+ git add .
![git-add img](./imgs/git-add.jpg)

### 提交到工作区
+ git commit -m "first commit"

### 关联远程仓库
+ git remote add origin git@github.com:Henry-baobao/git-demos.git

### 推送到远程仓库
+ git push -u origin master
+ git push origin dev