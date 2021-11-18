# RaspberryPi-re3
 Raspberry Pi - GTA III, Vice City

Need to prepare:
-Raspberry Pi 4
- Raspbian [32bit](https://downloads.raspberrypi.org/raspios_lite_armhf/images/) / [64bit](https://downloads.raspberrypi.org/raspios_arm64/images/)
- GTA III/Vice City game files

Video tutorial: Please wait for the update

Installation step instruction (Command):
1) git clone https://github.com/CrashCortez/RaspberryPi-re3
2) chmod -R +x RaspberryPi-re3/*.sh
3) Run the following commands on your system

32bit system
```
To install GTA III
./RaspberryPi-re3/install_gta3.sh

To install GTA VC
./RaspberryPi-re3/install_gtavc.sh

upgrade
./RaspberryPi-re3/update.sh
```

64bit system
```
To install GTA III
./RaspberryPi-re3/install_gta3_64.sh

To install GTA VC
./RaspberryPi-re3/install_gtavc_64.sh

upgrade
./RaspberryPi-re3/update_64.sh
```

4) Enter the re3 folder, enter the gamefiles folder, copy all files and folders, and paste (overwrite all) into the GTA III/Vice City game folder
5) Enter the re3 folder, enter the bin folder, enter the linux-named folder, enter the Release folder, copy reVC, and paste (overwrite all) into the GTA III/Vice City game folder
6) Enter the GTA III/Vice City game folder
7) Type ./reVC to start the game

Suggest:
-After entering the game, adjust the game resolution to the lowest
-Overclocking arm_freq=2000 gpu_freq=600 over_voltage=6
-Personally feel that using a 64bit system is smoother
