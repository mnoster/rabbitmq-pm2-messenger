# rabbitmq-pm2-messenger





#### PM2 Commands
- PM2 takes care of application process cluserting and IPC
```
pm2 start process.json // Start process(es) via process JSON file.
pm2 ls // Show a list of all applications.
pm2 stop<app> // Stops a specific application.
pm2 start<app> // Starts a specific application.
pm2 <app>scale N // Scales the application you specify to N number of instances (can be used to scale up or down).
pm2 kill // Kills all running applications.
pm2 restart // Restarts all running applications.
pm2 reload // Reloads the app configuration (this comes in handy when you modify your application's environment variables).
```
