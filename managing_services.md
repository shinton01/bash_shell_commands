# Managing Services

systemctl: manages services

journalctl: manages logs


## systemctl commands

systemctl [command] [unit name] (unit is a service)

- **enable**: make sure unit always starts at boot
- **disable**: opposite of enable
- **start**: start unit now (will not start at boot)
- **stop**: stop running unit (will not disble at boot)
- **reload**: re-read the program config files (cinfig updates)
- **restart**: kill process and start it again, re-reading config files
- **status**: check status of unit, shows last few lines of log output

