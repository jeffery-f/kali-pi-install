# kali-pi-install

1) run df -h:  Make note of the disk that showed up (ie /dev/disk1s1
2) sudo diskutil umount /dev/disk1s1
3) sudo dd bs=1m if=~/Desktop/kali-2.12-rpi2.img of=/dev/rdisk1
4) sudo diskutil eject /dev/rdisk3
