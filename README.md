# ubuntu

# version 
`lsb_release -a`
`cat /etc/*-release`
`cat /etc/issue`


`sudo apt-get update`

`sudo apt-get upgrade`

`sudo apt install build-essential dkms linux-headers-$(uname -r)`*

# kernel antuguos eliminar

`uname -a`

`dpkg --list | grep linux-image`

`sudo apt-get purge linux-image-X.x.x-XX-generic`

`sudo update-grub`



# listado de paquetes

`dpkg --get-selections`

`dpkg --get-selections | grep php`

# version os
`lsb_release -a`
`cat /etc/*-release`
`cat /etc/issue`
