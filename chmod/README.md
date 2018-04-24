# chmod
---

语法
> chmod [-cfvR] [--help] [--version] mode file...

所有用户组添加可读权限
```bash
chmod ugo+r index.js
```

也可以用数字表示

> r=4,w=2,x=1，第一个数字位代表User，第二个表示Group，第三个是Other

```bash
chmod 777 index.js
```
