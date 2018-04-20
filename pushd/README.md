# cd/pwd/pushd/popd/dirs
---

## cd (change directory)
目录切换，切换到目标目录
```bash
cd ~/workspace/react-native-share
```
切回到上个目录
```bash
cd -
```
使用oh-my-zsh，可以省略cd输入，比如跳转到用户主目录
```bash
~ 
```
跳转到上级目录
```bash
.. 
```
跳转到再上一级目录
```bash
... 
```
## pwd (present working directory)
查看当前目录
```bash
pwd
```

## pushd & popd (push to directory, pop back)
> cd跳转到目标目录，也可以回到上次跳转过来的目录，但是当你跳转的目录较多的时候，你想去其中一个你曾经访问过的目录，cd是无法做到的，这个时候我们就使用pushd

跳转的目标目录，并将该目录加到堆栈内
```bash
pushd ~/workspace/react-native-share/share
```

pushd加上数字N，将第N个目录移动至栈顶并切换到该目录
```bash
pushd +2
```

交换栈上最上面的两个路劲
```bash
pushd
```



删除堆栈中的目录，若不需要跳转则加上参数n
```bash
pod -n
```

通过dirs来查看堆栈中的所有目录
```bash
dirs -v
```
