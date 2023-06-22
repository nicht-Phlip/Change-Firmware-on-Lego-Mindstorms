***This instruction requires a Windows computer***
The Lego MIndstorms Spike and Inventor hubs have the same hardware, and if you want to change the firmware to take advantage of the other system benefits, here you can find below a detailed description.

The initial step is to put the hub into device firmware update mode.
To achieve that, you must turn the hub off and then press the Bluetooth button. While you press, put the USB cable in that connects to your computer.
After a certain period, the Bluetooth button should commence blinking. Upon that occurrence, you must release the button.
Now that the hub is in DFU mode, you must open the device manager, search for "other devices," and select "LEGO Technic Large Hub in DFU Mode." Right-click on it and select "update drivers."
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/Screenshot%202023-06-21%20122228.png)

The next step will be to select from where you want to install the driver. In this case, you will have to choose "Browse my computer for drivers".
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/Screenshot%202023-06-21%20142839.png)

The subsequent step will be to choose from which source we will install the driver. The drive necessary for the hub is already stored on your computer, so you will need to select "Let me pick from a list of available drivers on my computer."
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/Driver.png)

Next, you need to choose which type of device the driver is for. In this case, it will be for a "Universal Serial Bus device"
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/select%20device%20type.png)

To install a device driver, first choose the manufacturer, which is called "WinUsb Device." Then choose the model, which is also called "WinUsb Device".

![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/choose-driver.png)

Windows will warn you that it does not recommend installing the driver on the hub, because it cannot verify that the driver is compatible with the hub. However, we will confirm with "yes" that we want to install the driver on the hub.
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/Warning.png)

After that, we have successfully installed the driver and will be able to close the window.
![](https://github.com/nicht-Phlip/Change-Firmware-on-Lego-Mindstorms/blob/main/images/Finish.png)

