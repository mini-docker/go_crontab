# crontab

## Cron 常见用法
- 每隔5分钟执行1次：*/5 * * * * echo hello > /tmp/x.log
- 每1-5分钟执行5次：1-5 * * * * /usr/bin/python/data/x.py
- 每天10点，22点整执行1次：0 10,22 * * * echo bye | tail -1




