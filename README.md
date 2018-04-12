
# Google AIY voice drivers for RaspberryPi


These scripts were cloned from the official [google](https://github.com/google)/[aiyprojects-raspbian](https://github.com/google/aiyprojects-raspbian)  repository.



## Preparation

1. Assemble your Google AIY project as explained in the MagPy magazine that comes with your AIY Voice Kit.

2. Install the O.S. of your choice (Raspbian / Arch / etc.) in your SD card.

3. Certify that there is internet conexion and **git** & **alsa** are installed.

4. Clone this repository in your home folder:

```
$ cd ~/ 
$ git clone https://github.com/raibtoffoletto/AIY-voice-driver
```

## Instalation
Enter the drivers directory:
```
$ cd ~/AIY-voice-driver/scripts/
```
Enable AIY HAT's drivers:
```
$ sudo bash configure-driver.sh
```
Restart your system:
```
$ sudo reboot
```
Install alsa configuration files:
```
$ sudo bash install-alsa-config.sh
```