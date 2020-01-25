## Instructions:
- First uninstall current realtek audio driver.
- Restart ur PC with Disable driver signature enforcement:

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Download driver "Realtek_UAD_DTS_v6.0*****.7z" from here [![Github all releases](https://img.shields.io/github/downloads/shibajee/realtek-uad-dts-mod/total.svg)](https://github.com/shibajee/realtek-uad-dts-mod/releases/) and extract it.

- Go to UAD_DTS folder and double click Setup.exe.

![alt text](https://i.postimg.cc/9QDrtMSq/Untitled-2.png)

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

- Enable Sideload apps:

Go to Settings > Update & Security > For developers > click Sideload apps and close.

- Now go to UWP_BUNDLE folder and run INSTALL_UWP_BUNDLE.bat as administrator. This will install Realtek and DTS HeadphoneX v1 UWP audio control panel. Installation is silent and will close automatically.

Wait 1 min to give time to install the UWP application properly.

- Restart ur PC and Enjoy DTS effects.


![alt text](https://i.postimg.cc/SRNn62hK/dtshpx1.png)
![alt text](https://i.postimg.cc/wx0y6VXR/dtshpx2.png)


## FAQ:

- Which Windows version is compatible ?

Windows 10 64bit RS5 1809 to latest whatever version.

- Why no 32bit support ?

ƒuck 32bit.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

At least once in every month.
