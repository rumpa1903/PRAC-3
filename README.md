# PRAC-3

SSH stands for secured shell .
 The ssh command provides a secure encrypted connection between two hosts over an insecure network.
 This connection can also be used for terminal access, file transfers, and for tunneling other applications.
 
 Commands:
 ->> $sudo apt-get -y install openssh-server
 
 ->> $sudo systemctl enable ssh
 
 (optional)-if required change the configurations from the sshd config file 
 
 ->> $sudo systemctl start ssh
 
 ->> (optional) $sudo systemctl status ssh
 
 ->>$sudo ssh localhost
 
 [then enter your root or user password whatever it may be]
