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

* ```
  git checkout main 
  ```

  切换到主分支

* ```
  git merge [分支名]
  ```

  将之前新建的分支合并到主分支

* ```
  git branch -d [分支名]
  ```

  删除之前建立的分支

* 再 add、commit 、push 一发

* 完成





注：若在 push 的时候发生报错

```
fatal: Need to specify how to reconcile divergent branches.
```

请先把你新写的代码或文档保存下来，然后输入指令：

```
git merge -X theirs
```

执行后你可能会发现你新写的代码没有了，这时候重新粘贴上去，在 add + commit + push 应该就没问题了