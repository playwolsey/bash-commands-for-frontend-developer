# touch
---

> 为什么要修改文件的时间戳？遇到文件无法编译的情况，有时候是第三方拷贝过来，编译文件的时间超过了当前编译器的时间，touch命令正是为了修改时间戳而存在的命令

新建一个空文件
```bash
touch index.js
```

同时创建多个文件
```bash
touch default.less index.less mixin.less
```

改变文件的访问时间
```bash
touch -a index.js
```

改变文件的修改时间
```bash
touch -m index.js
```
