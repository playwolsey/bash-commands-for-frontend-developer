# kill
---

强制关闭进程
> 需要知道你所要删除的进程的进程号，通过ps命令获取进程号
```bash
ps aux | grep chrome
username   26758   0.0  0.0  4258468    184 s003  R+    5:34PM   0:00.00 grep --color=auto --exclude-dir=.bzr --exclude-dir=CVS --exclude-dir=.git --exclude-dir=.hg --exclude-dir=.svn chrom
kill -9 26758
```
