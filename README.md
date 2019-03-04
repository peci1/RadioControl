# RadioControl
Windows Universal App that allows command-line control of radio devices

Install the app, and then you can use it from commandline like:

    radiocontrol.exe 0 on
    radiocontrol Bluetooth off
    
If you get problems like `command not found` and alike, please report them as an issue here. As a workaround, call the program by the absolute path:

    "%USERPROFILE%\AppData\Local\Microsoft\WindowsApps\radiocontrol.EXE"
    
[![Get app from Microsoft Store](https://assets.windowsphone.com/13484911-a6ab-4170-8b7e-795c1e8b4165/English_get_L_InvariantCulture_Default.png)](https://www.microsoft.com/store/apps/9PJBRHTBVNMR?ocid=badge)

## (Better) alternative

You can even control your radios without installing any app, just using a cmdlet described here: https://superuser.com/a/1293303/255660 .

## Supported platforms

Windows 10 Anniversary Update and newer (fall 2016+).

## Building

To build the app, you need to open the solution in Visual Studio 2017.

## Attributions

Icon: https://www.brandeps.com/icon/B/Bluetooth-03 (https://creativecommons.org/licenses/by-sa/4.0/)
