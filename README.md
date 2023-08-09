# Raspberry Pi - Configure WiFi headlessly using an AP

### Installation
```
git clone https://github.com/SourishS17/rpi-wifi-ap.git
cd rpi-wifi-ap/program/
chmod +x setup.sh 
sudo ./setup.sh 
```
Then, reboot or shutdown before use.


### Usage
1) Within 3 minutes of boot, if no WiFi is connected, an AP will appear (RPi-Cofigure-WiFi)
2) Connect to it with any device
3) A webpage should pop up (if not, try browsing the internet to force it to pop up)
4) Enter the desired WiFi credentials (**ensure they are correct**) and click the button
5) The Pi will now reboot and use these credentials.


### Dependencies 
The following packages are installed by `setup.sh`:
- hostapd
- dnsmasq
- nodejs
- npm
