The script I use for the complete cloning of my Raspberry Pi 4 - Ubuntu Server 24.04.3 LTS installed with PI Imager

> You need a USB SD card reader and an SD card of sufficient size for your system.
>
> The SD card can be smaller or larger, it doesn't matter.
> 
>Before performing the synchronization operations, we stop certain services that cause too much read/write traffic.
>
>In the script, I put 'service mysql start/stop' which corresponds to my case, so adapt it to your system.

Simply place the script in the root directory of your system.

`cd /`

`wget https://raw.githubusercontent.com/comdif/pibackup/refs/heads/main/clone`

`chmod 755 clone`

Insert your USB drive with the new card and enter:

`./clone`

Have a coffee and your card will be ready.
