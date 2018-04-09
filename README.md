# piroot
how to setup root account on RPi


sudo passwd root

sudo vi /etc/ssh/sshd_config

PermitRootLogin without-password
change to
PermitRootLogin yes

key x to delete then press i type in yes

sudo service ssh restart


pi gu
apt-get install python-matplotlib
apt-get install python-pandas
apt-get install python-bs4
apt-get install python-sklearn-pandas
pip install pandas_datareader

pip install pandas_datareader==0.5.0
