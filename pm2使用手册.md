#pm2 for node app 

- 安装：npm install -g pm2
- 启动程序：pm2 start <app_name|id|all> 
- 可以指定应用名称 pm2 start app,js --name=test
- 列举进程：pm2 list
- 退出程序：pm2 stop <app_name|id|all>
- 重起应用：pm2 restart
- 重载应用: pm2 reload
- 程序信息：pm2 describe id|all
- 监控：pm2 monit
- 实时集中log处理: pm2 logs
- API:pm2 web (端口：9615 )