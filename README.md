## Instructions:
- First uninstall current realtek audio driver, realtek uwp control panel and other 3rd party enhancement app like nahimic/dts/dolby/creative.
- Restart ur PC with Disable driver signature enforcement:

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Download driver "***_UAD_WHQL_DTS_2021.7z" from here [![Github all releases](https://img.shields.io/github/downloads/shibajee/realtek-uad-dts-mod/total.svg)](https://github.com/shibajee/realtek-uad-dts-mod/releases/) and extract it.

- Go to the extracted folder and double click Setup.exe.

![alt text](https://i.postimg.cc/9QDrtMSq/Untitled-2.png)

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

Wait a few minutes. DTS HPXv1, DTSX Ultra and Realtek control panel should download and install automatically in background if u have internet.

- Now if u see this 3 app in start menu after like 3~5 minute restart ur PC.

- After restarting ur PC, open those apps. Play a music file and try different presets or settings to ensure that DTS effects r working properly.

- In some situation 1/2 or all 3 app could be missing in start menu. That means they didn't download/install properly in background for some reason. In that case u can download those app from Microsoft store.

Quick shortcut code to download/install the UWP apps from Microsoft store, Windows Key+R and paste then hit enter:

`ms-windows-store://pdp/?PFN=DTSInc.DTSHeadphoneXv1_t5j2fzbtdg37r`

`ms-windows-store://pdp/?PFN=DTSInc.DTSXUltra_t5j2fzbtdg37r`

`ms-windows-store://pdp/?PFN=RealtekSemiconductorCorp.RealtekAudioControl_dt26b99r8h8gj`

- For some reason if u don't have Microsoft store (bcoz u have higher IQ than me) or u have trouble installing from store then just download the "UWP_Offline_BUNDLE.7z" and run "INSTALL_UWP_BUNDLE.bat" as administrator. U probably have to enable developer option before install offline apps.

- Enable Developer option:

Go to Settings > Update & Security > For developers > click to enable Developer Mode *ON* and close the window.


![alt text](/img/dtshpx1.png)
![alt text](/img/dtshpx2.png)
![alt text](/img/dtsxu1.png)
![alt text](/img/dtsxu2.png)
![alt text](/img/dtsdgent.png)
![alt text](/img/dtscint.png)


#### Uninstallation:

- First uninstall DTS HPXv1, DTSX Ultra and Realtek Audio Console UWP app from Start menu or Settings, after that uninstall realtek audio driver and then restart ur pc (if possible use [DDU](https://www.wagnardsoft.com/forums/viewtopic.php?f=5&t=2747) for clean driver uninstallation)

#### Update:

- Uninstall current mod by above then install new driver.


## FAQ:

- Which Windows version is compatible ?

Windows 10 64bit 20H2 to latest whatever version. If u have older version use at ur own risk.

- Why no 32bit support ?

ƒuck 32bit.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

When I have free time.
