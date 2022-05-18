## 同环境多git用户切换

```

git config --global user.name "Your_Username"
git config --global user.email username@xxx.com

#然后，看一下这个文件：
vim ~/.gitconfig
```
## 增加/删除 fork 的 pull request 地址

The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use    

    git push --set-upstream origin master