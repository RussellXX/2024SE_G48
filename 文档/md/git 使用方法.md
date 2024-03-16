# git 使用方法

* 先保证有一个 github 账号，并在网站上接收邀请加入项目

* ```
  git clone https://github.com/RussellXX/2024SE_G48
  ```

  拉取项目文件夹，此时处于主分支

* ```
  git checkout -b [分支名]
  ```

  写之前记得新建一个分支，分支名自取。该指令执行成功会自动跳转到新建的分支

* 在该分支上写文档或代码

* 写完后先在该分支上 add + commit 一发

* ```
  git checkout -b main 
  ```

  切换到主分支

* ```
  git merge [分支名]
  ```

  将之前新建的分支合并到主分支

* 再在主分支上 add、commit 一发，此时加上 push

* 完成