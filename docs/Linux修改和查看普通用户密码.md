---
link: https://anomanm.notion.site/Linux-3bd4a0edb3a6494e88511289744abe07
notionID: 3bd4a0ed-b3a6-494e-8851-1289744abe07
---
**1.** root修改普通用户的密码：

```bash
sudo passwd user_name
```

然后连续两次输入新的用户密码即可；

2.root查看普通用户密码:

**密码是无法被查看的，即使是root也不行**，因此普通用户要是遗忘了密码，可以参照上一步，让管理员使用root权限修改密码，然后再将新密码告知普通用户；

3.普通用户修改密码：

```bash
passwd
```