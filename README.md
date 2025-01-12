# lightnote-update

## Setup

Before proceeding, please make sure that you have the following:

1. [balenaEtcher](https://etcher.balena.io/#download-etcher) installed on your host.

2. A suitable type-C cable that will allow you to connect your Lightnote to
   your laptop/PC.  Depending on your system, the cable will be like one of the
two options below:

![](images/usb-c-to-usb-a.png) ![](images/usb-c-to-usb-c.png)

3. Your [Lightnote](https://lightnote.cardonabits.com/products/lightnote-chess-edition-2-0)

![](images/TopViewLandscape.png)

4. A ROM file that you may have obtained from Cardona Bits or from [this repository](roms)

## Steps

1. Attach lightnote to your host and press the lightnote pushbutton until you see the USB icon on the screen.

![lightnote-usb](https://github.com/cardonabits/lightnote-update/assets/676181/a7aaa4d2-c884-46f2-8fa8-d46262f34f7e)


> [!NOTE]
> On MacOS you may get the following error, which is OK to ignore:
>
> ![](images/readable-error.png)

2. Launch balenaEtcher and select 'Flash From File'. 

![](images/flash-from-file.png)

3. Select `All` types of file, then pick the lighnote ROM file you want to install.

![](images/all-images.png)
![](images/select-file.png)

> [!NOTE]
> You will get a warning about a missing partition table.  It is OK to ignore it.
>
> ![](images/missing-partition-table.png)

4. Select your installation target to be `Lightnote Media`

![](images/select-target.png)
![](images/lightnote-media.png)

> [!NOTE]
> You may be asked to enter your user password to gain priviledges to write to an external disk.
>
> ![](images/priviledge.png)

5. Start flashing, and go for a cup of tea:  the flashing process takes about 5 minutes.

![](images/flash.png)
![](images/flashing.png)
![](images/flashed.png)

6. Now you can detatch your Lighnote and press the pushbutton to see the new content.

