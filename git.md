## git init 

项目初始化 生成.git文件（本地仓库）
代码状态为U

## 自报家门
只需全局设置一次即可
git config --global user.name "xiaoming"
git config --global user.email 1756329434@qq.com


## 把本地开发代码存到.git本地仓库

### git add . 
git add . 代码状态为A (暂存区) 一旦代码有改动就一定要执行此命令。
如果还在修改本代码 状态有A变为M
### git commit -m "放了git.md"

这一步把代码就放在了本地git中
### git commit --all -m "一次性操作"
把所有修改的代码直接提交到本地仓库。

工作区-->暂存区-->版本库（本地仓库）
## git log --oneline
查看本地提交的每一次信息。代码发生改动但是没有

## git branch
查看所有本地分支

## git branch dev
新建分支dev dev为了好理解。任意取名字

## git checkout dev 
切到新建的dev分支上







