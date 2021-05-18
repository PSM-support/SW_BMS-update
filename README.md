# SW_BMS-update 
Sunwoda BMS update v.1.5 (Windows) for PSM

**For BCMU 1.16** please use **SW_Modbus-software** to initialize the default parameters:  

https://github.com/PSM-support/SW_Modbus-software

The Sunwoda BMS update software uses CAN interface for communication with the PSM controller module. 
PCAN-USB is supported by default. 

![PCAN-USB](https://www.peak-system.com/uploads/tx_commerce/rte/RTEmagicC_PCAN-USB_Group_2014.jpg.jpg)
*pic from manufacture's web site*

**Step 1** : download and install PCAN-USB driver for Windows

https://www.peak-system.com/quick/DrvSetup

**Step 2** : download the Sunwoda BMS update PC software

https://github.com/PSM-support/SW_BMS-update/tree/master/download/Ruidian_update_v1.5.rar

**Step 3** : extract *Ruidian_update_v1.5.rar* into your working folder. 

7-zip (Direct Download: https://www.7-zip.org/a/7z1900-x64.exe) is a GNU archiver is recommended for *RAR*. 

**Step 4** : Run *javaw.exe* then follow instruction thereafter. 

##### It is important to exit the software before physically disconnecting the CAN cable. 

## User interface
### Page 1 : to change the number of battery connected
![SM snapshot](/pic/SU_BMS-P1.png)

### Page 2 : update the firmware to the latest version
![SM snapshot](/pic/SU_BMS-P2.png)

**Note for P01 controller:** the BMS system will automatically shut down at clicking the "REFRESH" button; pls manually turn on the controller before clicking "UPDATE ..". 

### Prompt at the start up 
![SM snapshot](/pic/SU_BMS-note1.png)

Please close other PCAN connection before proceeding.
