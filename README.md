# piroot
how to setup root account on RPi


sudo passwd root

sudo passwd -- unlock root

sudo vi /etc/ssh/sshd_config

PermitRootLogin without-password
change to
PermitRootLogin yes

key x to delete then press i type in yes

sudo service ssh restart
