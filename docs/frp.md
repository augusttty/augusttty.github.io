### 服务端配置示例

```bash
# frps.ini
[common]
bind_port = 7000

# Enable frp dashboard
dashboard_addr = 0.0.0.0
dashboard_port = 7500
# Dashboard's username and password are both optional
dashboard_user = username
dashboard_pwd = passwd

# Enable authentication
authenticate_new_work_conns = true
authentication_method = token
token = yourToken
```