# Cron Jobs
### - Cron: is a utility program that lets users input commands for scheduling tasks repeatedly at a specific time.
### - Cron Job: a job scheduler on Unix-like operating systems.
- With cron jobs, users can automate :
 - System maintenance
 - Disk space monitoring
 - Schedule backups
 
### In linux, we can add (tasks||jobs) by this commabd :
```
 ┌───────────── minute (0 - 59)
 │ ┌───────────── hour (0 - 23)
 │ │ ┌───────────── day of the month (1 - 31)
 │ │ │ ┌───────────── month (1 - 12)
 │ │ │ │ ┌───────────── day of the week (0 - 6) (Sunday to Saturday;
 │ │ │ │ │                                   7 is also Sunday on some systems)
 │ │ │ │ │
 │ │ │ │ │
 * * * * * <command to execute>
```

Resources

[Wikipedia](https://en.wikipedia.org/wiki/Cron)

[HOSTINGER TUTORIALS](https://www.hostinger.com/tutorials/cron-job#What_Is_a_Cron_Job)


