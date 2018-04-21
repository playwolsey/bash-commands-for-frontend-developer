# rm
> 文件一旦通过rm命令删除，则无法恢复，所以必须格外小心地使用该命令。谨慎使用参数-f
---

删除文件
```bash
rm index.js
rm：是否删除 一般文件 “index.js”? y
```

删除目录
```bash
rm -r ~/workspace/
```

强制删除目录及目录内文件
```bash
rm -rf ~/workspace/
```

建议使用-i参数，更安全
```bash
rm -i ~/workspace/import.import
```
