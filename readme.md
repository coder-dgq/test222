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
- .gitignore文件的作用：不提交指定路径的文件到仓库,创建.gitignore文件并提交到仓库，写法：
    + *`/.idea` 忽略.idea文件
    + *`/ddd` 忽略ddd文件夹所有文件
    + *`/ddd/*.js` 忽略ddd目录下所有js文件
- git reflog可以看到切换版本的记录以及所有提交的版本号
### 分支的创建和切换
- git branch dev (创建名为dev的分支，该分支刚创建时的内容与master分支的相同)
- git branch (查看当前有哪些分支)
- git checkout dev (切换到名为dev的分支)
### 合并分支
- git merge dev 把当前分支与指定分支（dev）进行合并
- git branch 输出结果中前面有*号的分支是当前分支
- 合并有时会冲突，需要手动处理，处理后再提交一次
### GitHub
- https://github.com(网站)
- GitHub网站提供了允许通过git上传代码的功能
### 提交代码到github（当作git服务器来用）
- `git push [地址] master`
    + 示例：`git push https://github.com/coder-dgq/test222.git master`
    + 把当前分支的内容上传到远程的master分支上
- `git pull [地址] master`(拉取数据，得到远程分支数据，注意这里要先在本地初始化一个仓库)
- `git clone [地址]`得到远程仓库的数据，多次执行会覆盖






