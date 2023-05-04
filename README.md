# add-ppa-debian
add-ppa-debian for debian 11/12

Usage : make the script executable and run it with sudo passing ppa as argument.

ex : 
sudo add-ppa-debian ppa:user/ppa-name

Using for mesa-kisak :

sudo add-ppa-debian ppa:kisak/kisak-mesa

Remove a PPA :
Go to /etc/apt/source.list.d/ and delete the .list file with the ppa name you want to.
