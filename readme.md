### 新建文件夹
### 文件夹中右键点击git bash
### 命令行输入git init来初始化仓库
### 用户名、邮箱
- git config --global user.name “xiaozhu”
- git config --global user.email “xiaozhu@xxx.com”
- 作用是每次备份都存储备份用户的信息
### 把代码放到“.git”仓库中
- git add ./readme.md
- git commit -m "存入readme"
- "存入readme"是一段说明
- 也可以“git add ./” （添加所有修改的文件）
### 修改提交
- q!回退界面
- 按git add “要提交的文件”，接着git commit -m "提交说明"的方式提交
### 查看当前状态
- git status
- 可以用来检查当前代码是否放入仓库中





