# 版本管理

## 命令

### 查看状态

````bash
git status
````


### 查看修改内容

```bash
git diff
```


### 查看提交历史

```bash
git log
```


### 查看命令历史

```bash
git reflog
```


### 丢弃工作区中的修改

```bash
git checkout -- filename.xxx
```


### 撤销暂存区中的修改

```bash
git reset HEAD <filename.xxx>
```


### 版本回退

```bash
git reset --hard commit_id
```

HEAD总是指向当前版本。


## 远程库

Git命令中，把远程库默认称为origin。

### 推送命令

```bash
git push -u origin master
```

Git不但会把本地的`master`分支内容推送的远程新的`master`分支，还会把本地的`master`分支和远程的`master`分支关联起来，在以后的推送或者拉取时就可以简化命令。
