# 通过不安全配置
通过suid可执行文件
通过capanilities可执行文件
通过sudo规则
https://gtfobins.github.io/
通过cron定时任务，注意高权限用户创建的任务
通过写passwd文件，新增用户
通过读shadow文件，爆破hash
# 通过高权限服务
管理员权限启动的服务，注意监听本地端口的进程
其他用户启动的服务，可能有sudo权限

# 通过系统漏洞

# 通过收集到的凭证信息