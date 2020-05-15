##### Recording anythins in my Road of Computer Learnning 
##### linux command：
  in linux, if permission denied to copy, then trying "sudo chmod -r 777" command for <target directory>.
  
###### git command：
  if you want to test Git SSH seting, command of "ssh -T git@github.com" can be used; and then input password.
  git status， 查看仓库状态
  git init, initialize repository
  git add <filename>，向暂存区添加文件
  git commit [-m "提交说明"], 提交，保存仓库的历史记录
  git log [--pretty=short], 查看提交日志,带pretty参数只显示第一行简述信息
  git log -p，查看提交所带来的改动
  git log <file/path name>, 显示相关文件或目录的日志
  git diff, 查看工作数和暂存区的区别
  git branch，显示分支一览表
  git checkout -b <分支名>, 创建分支，并切换到该分支
  git branch <分支名>,在当前位置创建分支，没有切换
  git checkout <分支名>,切换到分支 
  git checkout -，切换到上一分支
  
  对分支说明：创建分支不需要连接服务器，基于特定主题的作业在特性分支中进行，主题完成后在与master分支合并。只要保持这样的开发流程，就能够保证master分支的稳定，可以随时发布。
  通常master作为主干分支，主干分支没有开发到一半的代码，可以随时查看。有时我们需要让这个主干分支总是配置在正式环境中，有时又需要用标签Tag等创建版本信息，同时管理多个版本发布。拥有多个版本发布时，主干分支也有多个。
  
  git merge，合并分支
  git log --graph,用图表的形式输出提交日志，非常直观，很有用！
  git reset --hard <哈希值>，回溯历史版本,HEAD指向<哈希值>提交点
  git reflog，查看当前仓库的操作日志
  
