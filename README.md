# to.do.on.debian8
TO DO AFTER INSTALL DEBIAN 8 JESSIE
----------------------------------------------


■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
■   _      _                    _____                 _       _   _               ■
■  | |    (_)                  |  __ \               | |     | | (_)              ■
■  | |     _ _   _ _ __ __  __ | |__) |_____   _____ | |_   _| |_ _  ___  _ __    ■
■  | |    | | | | | '_ \\ \/ / |  _  // _ \ \ / / _ \| | | | | __| |/ _ \| '_ \   ■
■  | |____| | |_| | | | |>  <  | | \ \  __/\ V / (_) | | |_| | |_| | (_) | | | |  ■
■  |______|_|\__,_|_| |_/_/\_\ |_|  \_\___| \_/ \___/|_|\__,_|\__|_|\___/|_| |_|  ■ 
■                                                                                 ■
■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■

            _   _   _   _   _     _   _   _   _   _   _   _   _   _   _  
           / \ / \ / \ / \ / \   / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ 
         ●( L | i | u | n | x ) ( R | e | v | o | l | u | t | i | o | n )●
           \_/ \_/ \_/ \_/ \_/   \_/ \_/ \_/ \_/ \_/ \_/ \_/ \_/ \_/ \_/ 

                     ●●●►+-+-+-+-+-+ +-+-+-+-+-+-+-+-+-+-+◄●●●
                         |L|i|u|n|x| |R|e|v|o|l|u|t|i|o|n|
                     ●●●►+-+-+-+-+-+ +-+-+-+-+-+-+-+-+-+-+◄●●●

                            ○○○○○►+-+-+-+-+-+-+-+-+◄○○○○○
                                 |2|L|i|u|x|.|o|r|g|
                            ○○○○○►+-+-+-+-+-+-+-+-+◄○○○○○


⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●-------->

su 
nano /etc/apt/sources.list

## Debian debian stable
deb http://ftp.ru.debian.org/debian stable main contrib non-free
deb-src http://ftp.ru.debian.org/debian stable main contrib non-free

## Debian jessie-updates
deb http://ftp.debian.org/debian/ jessie-updates main contrib non-free
deb-src http://ftp.debian.org/debian/ jessie-updates main contrib non-free

## Debian security
deb http://security.debian.org/ jessie/updates main contrib non-free
deb-src http://security.debian.org/ jessie/updates main contrib non-free

## Multimedia
deb http://www.deb-multimedia.org/ jessie main non-free

apt-get update
apt-get -f install
apt-get install deb-multimedia-keyring
apt-get update
apt-get upgrade

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> dbu-deb-packages

●--------> Add Linux Mint LMDE

su -

nano /etc/apt/sources.list

## Linux Mint LMDE
deb http://packages.linuxmint.com debian import

apt-get update
gpg --keyserver pgp.mit.edu --recv-keys 3EE67F3D0FF405B2
gpg --export 3EE67F3D0FF405B2 > 3EE67F3D0FF405B2.gpg
apt-key add ./3EE67F3D0FF405B2.gpg
rm ./3EE67F3D0FF405B2.gp

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install sudo

su
apt-get install sudo

nano /etc/sudoers

fouad ALL=(ALL:ALL) ALL

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Updates

One of the most important tasks is to keep your system updated.

su -

apt-get install apticron

apt-get install update-notifier-common

apt-get install debian-goodies

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install firmware-linux-nonfree

apt-get install firmware-linux-nonfree

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Gdebi

su -c 'apt-get install gdebi'

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install git

apt-get install git

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install python-vte

apt-get install python-vte

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install the “good stuff

apt-get install unrar rar handbrake handbrake-gtk soundconverter gstreamer0.10-plugins* h264enc easytag lame libdvdread4 libdvdcss* easytag flashplugin-nonfree cuetools shntool

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install NTFS support

apt-get install ntfs-3g

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install gtk2-engines

apt-get install gtk2-engines-murrine murrine-themes

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●●●●● System tools ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Diff tools

apt-get install meld
apt-get install diffuse

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Partition editor

apt-get install gparted

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Hardware info

apt-get install lshw lshw-gtk
apt-get install hardinfo
apt-get install sysinfo

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install SMART monitor

apt-get install smartmontools
apt-get install gsmartcontrol

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install htop

apt-get install htop

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Tools

apt-get install filezilla
apt-get install galculator

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Zip Tools

apt-get install unar

apt-get install zip

apt-get install unzip

apt-get install p7zip p7zip-full p7zip-rar

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install keepassx password manager

apt-get install keepassx

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install CopyQ 2.2.0 On Ubuntu, Linux Mint

32 bit OS

wget sourceforge.net/projects/copyq/files/copyq-2.2.0/Linux/copyq_2.2.0_Ubuntu_14.04_i386.deb

dpkg -i copyq_2.2.0_Ubuntu_14.04_i386.deb

64 bit OS

wget sourceforge.net/projects/copyq/files/copyq-2.2.0/Linux/copyq_2.2.0_Ubuntu_14.04_amd64.deb

dpkg -i copyq_2.2.0_Ubuntu_14.04_amd64.deb

----------> To remove CopyQ, do:

apt-get remove copyq

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


●●●●● INTERNET ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Firefox

Remove Iceweasel. What is Iceweasel?

su -

apt-get remove iceweasel

Add the following line to your package sources (/etc/apt/sources.list)

nano /etc/apt/sources.list

##Firefox
deb http://downloads.sourceforge.net/project/ubuntuzilla/mozilla/apt all main

install the necessary key

apt-key adv --recv-keys --keyserver keyserver.ubuntu.com C1289A29

apt-get update

apt-get install firefox-mozilla-build

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Google Chrome

su -

nano /etc/apt/sources.list

##Google Chrome
deb http://dl.google.com/linux/chrome/deb/ stable main

install the necessary key
	
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -

apt-get update

apt-get install google-chrome-stable

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Flash

apt-get install flashplugin-nonfree

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install OpenJDK

----------------------------------------------------

●--------> Install Oracle Java 8 (both JDK8 and JRE8) in Debian

su -

echo "deb http://ppa.launchpad.net/webupd8team/java/ubuntu trusty main" | tee /etc/apt/sources.list.d/webupd8team-java.list

echo "deb-src http://ppa.launchpad.net/webupd8team/java/ubuntu trusty main" | tee -a /etc/apt/sources.list.d/webupd8team-java.list

apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys EEA14886

apt-get update

apt-get install oracle-java8-installer

exit

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install Deluge torrent client

aptitude install deluge

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Transmission Torrent Download

apt-get install transmission

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install youtube-dl

apt-get install youtube-dl

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Dukto R6

32bit OS

sudo apt-get install gdebi
wget download.opensuse.org/repositories/home:/colomboem/xUbuntu_12.04/i386/dukto_6.0-1_i386.deb
sudo gdebi dukto_6.0-1_i386.deb

64bit OS

apt-get install gdebi

wget download.opensuse.org/repositories/home:/colomboem/xUbuntu_12.04/amd64/dukto_6.0-1_amd64.deb

gdebi dukto_6.0-1_amd64.deb

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install RSS Atom feed reader

apt-get install quiterss

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install DropBox

aptitude install nautilus-dropbox

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install megasync
mega.co.nz

DOWNLOAD SYSC

https://mega.nz/#sync!linux

OR

wget https://mega.co.nz/linux/MEGAsync/debian8.0/i386/megasync-Debian_8.0_i386.deb

gdebi megasync-Debian_8.0_i386.deb

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install surf

apt-get install surf

surf http://calendar.google.com

---------------------------------------------
https://pythonhosted.org/SuRF/install.html

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install radiotray radio

apt-get install radiotray

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


●●●●● MULTIMEDIA ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install codecs

apt-get install libavcodec-extra

apt-get install gstreamer0.10-plugins-ugly gstreamer0.10-plugins-bad gstreamer0.10-fluendo-mp3 gstreamer0.10-pulseaudio

apt-get install libgstreamer-perl libgstreamer-interfaces-perl

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install totem

apt-get install totem

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install dragon player

apt-get install dragonplayer

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install SMPlayer

apt-get install smplayer

## SMTube - YouTube browser for SMPlayer

apt-get install smtube

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


●●●●● Office ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Add Arabic language package FOR libreoffice

apt-get install libreoffice-l10n-ar

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Fonts

Install Microsoft fonts
	
apt-get install ttf-mscorefonts-installer

I use terminus font in Terminal:
	
apt-get install xfonts-terminus

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install PDF viewer

apt-get install evince

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Text editors

● Leadpad is a simple text editor

apt-get install leafpad

● Geany is an advanced text editor

apt-get install geany

● Gedit

apt-get install Gedit

● Kate

apt-get install Kate

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇






●●●●● Photo editing & shot tool ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Screenshot tool

apt-get install shutter

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install Screen record

apt-get install vokoscreen

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇
⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


●●●●● Theme & Icon ●●●●●

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install whiskermenu-plugin

https://qa.debian.org/developer.php?login=pkg-xfce-devel@lists.alioth.debian.org#gigolo

apt-get install xfce4-whiskermenu-plugin

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install libxfce4ui-1-dev package in Debian Wheezy

apt-get install libxfce4ui-1-dev

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install hijra

apt-get install hijra-applet

●To remove

apt-get remove hijra-applet

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install screensavers

apt-get install xscreensaver-gl

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Setting Timezone change

su -

dpkg-reconfigure tzdata

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Email notification

Run on click: thunderbird
Run on New Messages: notify-send "New mail" "You have new messages in your inbox" -i xfce-newmail

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Terminal Drop-down

► xfce4-terminal
► Ctrl + Alt + T

► xfce4-terminal --drop-down
► F12

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install numix themes 

su

apt-get install git

apt-get install docky

exit

mkdir numix

cd numix

git clone https://github.com/cldx/numix-gtk-theme

git clone https://github.com/numixproject/numix-icon-theme

git clone https://github.com/numixproject/numix-icon-theme-circle


● Create folder .icons
● Create folder .themes

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install faenza icon

apt-get install faenza-icon-theme

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


برامج قد ترغب فى تنصيبها
برامج اختياريه

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install Webmin

Modify your packages sources:

su -	

nano /etc/apt/sources.list

##Webmin
deb http://download.webmin.com/download/repository sarge contrib
deb http://webmin.mirror.somersettechsolutions.co.uk/repository sarge contrib

wget http://www.webmin.com/jcameron-key.asc

apt-key add jcameron-key.asc

apt-get update

apt-get install webmin

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> Install GNU GCC Compiler and Development Environment

http://www.cyberciti.biz/faq/debian-linux-install-gnu-gcc-compiler/

apt-get update && apt-get upgrade

apt-get install build-essential

OR

apt-get install build-essential

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install dosfstools

apt-get install dosfstools

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇

●--------> install debsums

Debian Cleanup and find broken packages and reinstall them
https://raphaelhertzog.com/2011/02/21/debian-cleanup-tip-4-find-broken-packages-and-reinstall-them/

sudo debsums

aptitude reinstall libapt-pkg-perl

# Or with apt-get

apt-get --reinstall install libapt-pkg-perl

⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇⊆⊇


