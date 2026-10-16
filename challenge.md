## question1
answer: i am student . my home is /home/folder
commands : whoami, pwd
## question 2
answer: the server name is ubuntu-lab01, and it runs ubuntu 24.04.3 LTS
command: hostname, cat /etc/os-releade
##question 3
answer: the server has 1.9Gi of total RAM, and 4.0G of disk space is available
command : free -h, df -h /
##question 4
answer: the user that can log in with /bin/bash are root, student and git.
command: grep "/bin/bash" /etc/passwd
##question 5
answer: there are aroung 220 processes running right now
command ps aux | wc -l
##question 6
answer: lab5user was created and deleted during our lab session (recorded in auth.log)
command: sudo grep lab5user /var/log/auth.log

