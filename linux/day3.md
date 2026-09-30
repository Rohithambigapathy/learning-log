PROCESS MANAGEMENT 

ps
ps aux
ps -ef
top 
htop
ps = snapshot, ps -ef = detailed snapshot, ps aux = resource snapshot, top = live monitor, htop = interactive live monitor.
sleep 
ps aux | grep sleep
kill <PID>
cd /var/log
grip -i "error" logname
tail -20 syslog
tail -f syslog

