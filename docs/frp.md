---
link: https://anomanm.notion.site/frp-46d2f690539142a1b37612e511b18626
notionID: 46d2f690-5391-42a1-b376-12e511b18626
---
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