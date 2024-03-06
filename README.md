# lightnote-update

## Setup

Before proceeding, please make sure that you have the following:

1. [balenaEtcher](https://etcher.balena.io/#download-etcher) installed on your host.
2. A suitable type-C cable that will allow you to connect your Lightnote to your laptop/PC. 
![](images/usb-c-to-usb-a.png)
![](images/usb-c-to-usb-c.png)
3. Your lightnote
4. A ROM file that you may have obtained from Cardona Bits or from this repository (`roms/lightnote-*.rom`)

## Steps

1. Attach lightnote to your host and press the lightnote pushbutton once.
Note: On MacOS you may get the following error, which is OK to ignore:
![](images/readable-error.png)

2. Launch baleneEtcher and select 'Flash From File'. 
![](images/flash-from-file.png)

3. Select `All` types of file, then pick the lighnote ROM file you want to install.

![](images/all-images.png)
![](images/select-file.png)
Note: You will get a warning about a missing partition table.  That is OK to ignore.
![](images/missing-partition-table.png)

4. Select your installation target to be `Lightnote Media`
![](images/select-target.png)
![](images/lightnote-media.png)
Note:  You may be asked to enter your user password to gain priviledges to write to an external disk.
![](images/priviledge.png)

5. Start flashing, and go for a cup of tea:  the flashing process takes about 5 minutes.
![](images/flash.png)
![](images/flashing.png)
![](images/flashed.png)

6. Now you can detatch your Lighnote and press the pushbutton to see the new content.

