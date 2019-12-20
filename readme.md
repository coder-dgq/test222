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
- 也可以用“git add ./” （把所有修改的文件添加到仓库）
- git commit --all -m "一些说明" (一次性把修改的文件提交到版本库)
### 修改提交
- q!回退界面
- 按git add “要提交的文件”，接着git commit -m "提交说明"的方式提交
### 查看当前状态
- git status
- 可以用来检查当前代码是否放入仓库中
### 查看日志
- git log
- git log --oneline (简洁版日志)
- .gitignore文件的作用：不提交指定路径的文件到仓库,写法：
    + *`/.idea` 忽略.idea文件
    + *`/ddd` 忽略ddd文件夹所有文件
    + *`/ddd/*.js` 忽略ddd目录下所有js文件







