# tick

Homework on TICK stack for monitoring course

## Alerts

**Server Resources Alerts**

Alert rules for server resources are displayed in the following table:

| Severity | CPU Usage | Memory Usage | Disk Usage | Disk I/O | Network |
|---|---|---|---|---|---|
| **Info** |  >70% for 5min or more | >80% for 5min or more | >80% | Read/Write > 80% | packet_loss>1%
| **Warning** | >80% for 2min or more | >90% for 2min or more | >90% | Read/Write > 90% | packet_loss>3%
| **Critical** | >90% for 1min or more | >95% for 1min or more | >95% | Read/Write > 95% | packet_loss>5%