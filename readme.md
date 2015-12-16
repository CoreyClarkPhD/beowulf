#Beowulf.1 Computes Cluster

[![Beowulf.1](https://cdn-images-1.medium.com/max/1600/1*eSi20Ri25vGSdoSfZL17FA.jpeg)](https://medium.com/computes-io/beowulf-1-powered-by-computes-io-supercomputer-cc227e85f17b#.emum6g4sc)

Beowulf.1 is the first [beowulf](https://en.wikipedia.org/wiki/Beowulf) mini-supercomputer built to run on [computes.io](http://computes.io). It was built using a single gigabit ethernet switch with four Raspberry Pi 2s. Each RPi2 has four cores making this cluster a 16-core mini-supercomputer!

You can clone this [raspberrypi.dmg](https://www.dropbox.com/s/gomchawunajogix/raspberrypi.dmg?dl=0) image on an SD card and boot up one or more of your own Raspberry Pis to join our distributed computing platform.

Here are the steps to clone your SD card:

1. diskutil list
2. diskutil unmountDisk /dev/disk2
3. sudo newfs_msdos -F 16 /dev/disk2
4. sudo dd if=~/Desktop/raspberrypi.dmg of=/dev/disk2


[More information on cloning and restoring SD card images](http://computers.tutsplus.com/articles/how-to-clone-raspberry-pi-sd-cards-using-the-command-line-in-os-x--mac-59911)
