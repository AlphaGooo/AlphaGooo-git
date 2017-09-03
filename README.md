# AlphaGooo-git
个人git使用技巧累积，不定期更新。

- [异常处理.md](files/异常处理.md)



## 基础命令



* 常用命令
  * git init # 初始化本地git仓库（创建新仓库）

  * git config --global user.name "xxx"  # 全局配置git用户名

  * git config --global user.email "xxx@xxx.com"  # 全局配置git邮箱

  * git clone git+ssh://git@192.168.53.168/VT.git # clone远程仓库

  * git status # 查看当前版本状态

  * git add  # 添加修改

  * git commit -m '...' # 提交修改，并附上修改说明

  * git rm xxx # 删除某个文件

  * git rm -r xxx # 递归删除（文件夹）

  * git log # 显示提交日志

  * git tag # 显示已存在的tag

  * git tag -a V2.0 -m 'XXX' # 增加V2.0的tag

  * git diff # 显示所有未添加的变更

  * git diff HEAD^ # 比较与上一个版本的差异

  * git branch # 显示本地分支

  * git branch -a # 显示所有分支

  * git checkout v2.0 检出版本v2.0

    ​

    参考网址：https://gist.github.com/guweigang/9848271