# RasQberry Installation and Setup

## Write the RasQberry Image to your SD card

0. Fetch the RasQberry-Two image from the source
1. Download & Install the [Raspberry Pi Imager](https://www.raspberrypi.org/software/). This is needed inorder to install the image to the microSD card. 
2. Put a formatted microSD into an SD card reader in your computer 
3. To run Pi Imager, select the Raspberry Pi device, the Operating system to use and the storage to write to. 
![rasp-imager-01](rasp-imager-01.png)
Select `Raspberry Pi Device` 
![rasp-imager-02](rasp-imager-02.png)
Choose OS – Select `Use Custom` to select an image from your location
![rasp-imager-03](rasp-imager-03.png)
Choose Storage and select your SD you inserted in step 2 (e.g. Apple SDCX Reader
Media xxx GB). Here we used the `MassStorageClass Media - 63.9 GB`
![rasp-imager-04](rasp-imager-04.png)
Select `Next`
![rasp-imager-05](rasp-imager-05.png)
Next, you can choose to customize the installation now or later. We will do that now. Select `Edit Settings`. 
![rasp-imager-06](rasp-imager-06.png)
In the general tab select `Set locale settings` (e.g. for Germany time zone: Europe /
Berlin and Keyboard layout: de). User configuration here is optional. The standard
user is raspberry with the pwd: rasqberry. Specify the username and password you would like to use. You can also choose to specify the WLAN settings now. 
![rasp-imager-07](rasp-imager-07.png)
Modifications of the service tab is also optional. Here, we `Enable SSH` for ease of administration. 
![rasp-imager-08](rasp-imager-08.png)
You can also optionally select the checkboxes under the `Options` tab as shown in the picture below. 
![rasp-imager-09](rasp-imager-09.png)
Select `Yes` button to apply the OS customization settings.
![rasp-imager-10](rasp-imager-10.png)
That prompts you to erase all data. Click `Yes` to erase all existing data from the SD card and copy the above selected Rasqberry image to the SD card
![rasp-imager-11](rasp-imager-11.png)
The writing process for the RasQberry pi image starts now and will be completed after verification of the writing process.
![rasp-imager-12](rasp-imager-12.png)
Take the SD card out of the SD card reader and put it into your Raspberry.
![rasp-imager-13](rasp-imager-13.png)
Power the Raspberry Pi on and the Rasberry pi will boot.

## One-Click Install 

```
$ sudo raspi-config 
```
![oneclick-01](oneclick-01.png)
started 00:10 
![oneclick-02](oneclick-02.png)

finished 00:15 - took 5 minutes 
![oneclick-03](oneclick-03.png)

```
Successfully installed qiskit-1.1.2
qiskit                 1.1.2
qiskit-qasm3-import    0.5.0
```