### 查看ip地址

```bash
ip addr | grep eth0
```

### wsl网络映射到windows

```bash
# 设置 wsl（ip为172.26.142.20）的 3000 端口映射到windows本地的 3000 端口
netsh interface portproxy add v4tov4 listenport=3000 listenaddress=0.0.0.0 connectport=3000 connectaddress=172.26.142.20

#删除代理
netsh interface portproxy delete v4tov4 listenport=3000 listenaddress=0.0.0.0 protocol=tcp
```

### 打开资源管理器

```bash
explorer.exe .    //wsl 打开文件浏览器
```

### 启动/停止

```powershell
wsl //启动wsl
wsl --shutdown //终止wsl
```