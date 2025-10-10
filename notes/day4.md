Process and Monitoring in Linux


ps aux | grep -1 ssh

ps = process status

a = show process from all user
u = display user-oriented format
x = include process without a terminal (backgroud processes)

| = pipesymbol , take output from ps aux and feed to grep

grep = search/filter tool
-i = case-sensitive search
ssh = search term (will match "ssh,"SSH","SsH",etc)

top and htop

top = display real time system processes
htop = same as top but more functionality


Basic argument for top command :

q - quit
k - kill process (enter PID)
M - sort by memory usage
P - sort by cpu usage
1 - show individual cpu cores

yes > /dev/null & = stress test for cpu

systemctl status ssh - check system service status (example ssh)
