<h1 align="center">Baofeng UV-5R</h1>
<h3 align="center">Configuration images, manuals, general documentation and .csv format frequency configurations.</h3>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-UV-5R">
  <img src="https://img.shields.io/github/v/release/SamuelNetherway460/Baofeng-UV-5R">
  <img src="https://img.shields.io/github/release-date/SamuelNetherway460/Baofeng-UV-5R">
  <img src="https://img.shields.io/github/issues/SamuelNetherway460/Baofeng-UV-5R">
  <img src="https://img.shields.io/github/downloads/SamuelNetherway460/Baofeng-UV-5R/total">
</p>

## Description
Repository for the Baofeng UV-5R digital radio. Contains all documents relating to the radio i.e., specs, manuals, etc. There are 4 different configurations for HAM radio each in a different branch named after the privilages / frequencies programmed, i.e., PMR446 (licence free), Foundation (UK licenced), Intermediate (UK Licenced) and full (UK Licenced).

## Configuration Status
| Configuration | Last Commit | Latest Release | Release Date |
| :---: | :---: | :---: | :---: |
| PMR446        | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-UV-5R/Config-PMR446) | ![version](https://img.shields.io/badge/release-PMR446--vX.X.X-blue) | ![release-date](https://img.shields.io/badge/release%20date-XX--XX--XXXX-red) |
| Foundation    | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-UV-5R/Config-Foundation) | ![version](https://img.shields.io/badge/release-Foundation--vX.X.X-blue) | ![release-date](https://img.shields.io/badge/release%20date-XX--XX--XXXX-red) |
| Intermediate  | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-UV-5R/Config-Intermediate) | ![version](https://img.shields.io/badge/release-Intermediate--vX.X.X-blue) | ![release-date](https://img.shields.io/badge/release%20date-XX--XX--XXXX-red) |
| Full          | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-UV-5R/Config-Full) | ![version](https://img.shields.io/badge/release-Full--vX.X.X-blue) | ![release-date](https://img.shields.io/badge/release%20date-XX--XX--XXXX-red) |

## Radio Specs
- Earpiece / mic type : Kenwood Plug type
- Antenna : SMA -Female
- Frequency Range: 136-174  / 400-520MHz
- Tri-Color Display, Dual Freq. Display, Dual-Standby
- Output Power: 4 /1Watts
- 128 Channels 50 CTCSS and 104 CDCSS
- Built-in VOX Function
- 1750Hz Brust Tone
- FM Radio (65.0MHz-108.0MHz)
- LED Flashlight
- Large LCD Display
- High /Low RF Power Switchable
- 25KHz/12.5KHz Switchable
- Emergency Alert
- Low Battery Alert
- Battery Saver
- Time-out Timer
- Keypad Lock
- Monitor Channel
- Channel Step: 2.5/5/6.25/10/12.5/25KHz
- ROGER SET

## Chirp Radio Programming Guide
1. Download and install [Chirp](https://chirp.danplanet.com/projects/chirp/wiki/Home).
2. Download the source / radio images from the [Releases](https://github.com/SamuelNetherway460/Baofeng-UV-5R/releases) page.
3. Launch Chirp.  
![Chirp Launched](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Chirp%20Launched.png)
4. Connect the Baofeng UV-5R to the PC using the USB programming cable.
5. Turn on the radio.
6. In the menu bar, click "Radio" and then "Download From Radio".  
![Download From Radio](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Download%20From%20Radio.png)
7. Select the correct Port, Vendor and Model using the drop down boxes.
8. Click "Ok".
9. Click "Ok".  
![Baofeng UV-5R Instructions](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Baofeng%20UV-5R%20Instructions.png)
10. Wait for Chrip to finish cloning the current radio programming.  
![Cloning Programming](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Cloning%20Programming.png)  
    The current programming will then be displayed.  
![Current Programming](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Current%20Programming.png)
11. In the menu bar, click "File", then "Save As".  
![Save Backup](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Save%20Backup.png)
12. Navigate the File Explorer and click "Save" to save a backup of the current radio configuration.  
![Save Radio Image](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Save%20Radio%20Image.png)
13. In the menu bar, click "File", then "Open".  
![Open Radio Image File Menu Bar](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Open%20Radio%20Image%20File%20Menu%20Bar.png)
14. Navigate the File Explorer and select the Radio .img file.  
![Navigate to Radio Image File](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Navigate%20to%20Radio%20Image%20File.png)
15. Click "Open".  
![Open Radio Image File](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Open%20Radio%20Image%20File.png)  
The radio image file should now be loaded.  
![Radio Image File Loaded](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Radio%20Image%20File%20Loaded.png)
16. Custom configurations such as welcome messages should now be made.
17. Once ready to upload to radio, in the menu bar click "Radio", then "Upload To Radio".  
![Upload to Radio](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Upload%20to%20Radio.png)
18. Select the correct Port and click "Ok".  
![Select Port](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Select%20Port.png)
19. Click "Ok" when the instructions are displayed.  
![Baofeng UV-5R Upload Instructions](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Baofeng%20UV-5R%20Upload%20Instructions.png)
21. The radio image file will now be applied to the radio.  
![Uploading to Radio](https://github.com/SamuelNetherway460/Baofeng-UV-5R/blob/Documentation/res/Uploading%20to%20Radio.png)
23. Once the radio light has finished flashing, and the progress bar is complete / progress window has disappeared, the radio can be switched off and disconnected.
24. Radio programming is now complete and the radio is ready to be used.
