# Commands

tail -15 /var/log/nginx/access.log > tail-command.txt
ps aux | grep -i amazon
dig uvg.edu.gt
neofetch
free -m | grep Mem
df -m
ip address show
lsof -i TCP:80 -s TCP:LISTEN
netstat -tulpn
ss --tcp --numeric --processes --info --memory --summary state listening
hostnamectl | grep "hostname" && hostnamectl | grep "System"
ps aux --sort=-%mem
grep -c '404' /var/log/nginx/access.log
ss -tlnp | grep :80	nginx
lsof -i :80 	204536 204538 204539
ps -p 204536 -o pid,comm,%mem,rss && ps -p 204538 -o pid,comm,%mem,rss && ps -p 204539 -o pid,comm,%mem,rss
