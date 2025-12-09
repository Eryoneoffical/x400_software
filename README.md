
### The latest version is here: https://gitcode.com/xpp012/KlipperScreen



Welcome, this is the Klipper and Screen Software of Eryone Thinker X400 3D printer


### How to Upgrade?
There are 3 ways to update and don't forget to reboot the printer after that:
1. Upgrade the software from the SSH (username:`mks` password:`makerbase`)

```
cd ~
mv KlipperScreen KlipperScreen_bk
git clone https://github.com/Eryoneoffical/x400.git
~/KlipperScreen/all/git_pull.sh

```

2. Upgrade the software from the screen

`More-->System-->Update`

3. Upgrade the software from the farm3d webpage

go to https://eryone.club , then send `Update Software` command in the console page.


### How to Flash linux into the SDcard?
1. Download and unzip the img file from the google drive : https://drive.google.com/drive/folders/1htD4KUY9WmH9W7UyBleRF0uzNoNothT1?usp=sharing
2. Plugin the sdcard into the PC, and flashed it with the balenaEtcher.exe
3. Plugin the sdcard into the X400 printer,and power on the printer.
4. Get the CAN UUID numbers from the printer screen: Memu-->Console-->Send `W`  (note:not `w` but `W`)
5. Back to the Menu and click: Firmware Restart, if it failed please restart the printer and run  Memu-->Console-->Send `W`  again.

### orca slicer
It is recommended that you use this OrcaSlicer, which has been configured for the X400.
https://ln5.sync.com/4.0/dl/2515edb40#fykktwzu-v5tzvm7v-a7s3fay8-5wssn4u6
https://drive.google.com/drive/folders/1htD4KUY9WmH9W7UyBleRF0uzNoNothT1?usp=drive_link

### Software of Farm3D 
More information: [https://github.com/Eryone/farm3d](https://github.com/Eryone/farm3d)

