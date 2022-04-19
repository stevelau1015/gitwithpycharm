# gitwithpycharm
# git使用
熟悉一下git的使用，重点是集成到pycharm中的使用

## 创建
自己单独创建一个项目，创建dev分支，从dev分支创建test分支，dev分支修改文件，test分支修改文件，
## 合并
 **把test分支合并到dev** by：git merge test,
 **合并过程中要有冲突**（这个过程必须有）
 此时出现修订界面，编辑代码后完成合并
## 解决冲突
通过代码的对照和在最终位置的修改，已经解决了冲突
## 更新
将最近版本更新到test环境中 git checkout test； git merge dev
## 版本回滚
