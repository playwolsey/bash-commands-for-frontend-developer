# kill
---

强制关闭进程

> 需要知道你所要删除的进程的进程号，通过ps命令获取进程号
```bash
ps aux | grep chrome
kill -9 26758
```

使用Alfred的工作流kill process直接输入kill chrome同样可以完成，不需要再查进程号
