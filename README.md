# Commands

```bash
curl http://35.239.213.125/
```

```bash
tail -15 /var/log/nginx/access.log > tail-command.txt
```

```bash
ps aux | grep -i amazon
```

```bash
dig uvg.edu.gt
```

```bash
neofetch
```

```bash
free -m | grep Mem
```

```bash
df -m
```

```bash
ip address show
```

```bash
lsof -i TCP:80 -s TCP:LISTEN
```

```bash
netstat -tulpn
```

```bash
ss --tcp --numeric --processes --info --memory --summary state listening
```

```bash
hostnamectl | grep "hostname" && hostnamectl | grep "System"
```

```bash
ps aux --sort=-%mem
```

```bash
grep -c '404' /var/log/nginx/access.log
```

```bash
ss -tlnp | grep :80	nginx
```

```bash
lsof -i :80 	204536 204538 204539
```

```bash
ps -p 204536 -o pid,comm,%mem,rss && 
ps -p 204538 -o pid,comm,%mem,rss && 
ps -p 204539 -o pid,comm,%mem,rss
```
