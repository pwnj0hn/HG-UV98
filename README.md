# HG-UV98
Firmware + tips &amp; tricks for the Lanch HG-UV98 APRS Radio

## Firmware in repo
* HG-UV98 September 23rd 2020 APRS firmware.zip - September 23rd 2020 APRS firmware
* V1.0.1_190619-KT.zip - KT2KT's version
* UV98_868_220430_S4.exe - APRS update from 30th of April 2022 (Fixes issue with wrong GPS coordinates reported)

## Software in repo
* HG-UV98 EN V2.0 setup.rar - English radio software v2.0 (Not especially good, but it works.)
* APRS 51TNC-ENG.zip - APRS software (I am not getting this to work..)
* APRS_51Serial_20181009.rar - APRS software


## Using the Radio software
To be able to write to or read from the radio with the programming software, the radio needs to be turned on when holding the lower side key (PF2). You will then get another boot screen with some Chinese characters.

## Using the APRS software
To be able to write or read APRS settings from the radio, the radio needs to be turned on when holding the middle side key (PF1).


## How to update radio firmware
* Download and install TeraTerm (https://osdn.net/projects/ttssh2/releases/)

* Choose serial port

![](/Images/teraterm-serialport.png)

* Choose serial speed

![](/Images/teraterm-serialport-speed01.png)
![](/Images/teraterm-serialport-speed02.png)

* Start radio in update mode by holding PTT and turn it on
* Type 1
* Choose file to upload

![](/Images/teraterm-serialport-upload.png)
![](/Images/teraterm-serialport-upload01.png)
![](/Images/teraterm-serialport-upload02.png)

* Wait for upload to finish
* Restart radio
* Note that if you have some problems using TeraTerm, try HyperTerminal instead - https://www.hilgraeve.com/hyperterminal-trial/)


## Links
* https://github.com/marrold/HG-UV98
* https://hvdnnotebook.blogspot.com/2019/10/review-lanch-hg-uv98-aprs-2m70cm-ht.html
* https://hvdnnotebook.blogspot.com/2021/02/sure-to-ok-fixing-hg-uv98.html
* https://www.venus-itech.com/product/hg-uv98-handheld-with-aprs/#comment-2062
* https://groups.io/g/HG-UV98-users/
