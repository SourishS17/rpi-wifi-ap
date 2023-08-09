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
1) If the RPi isn't connected to WiFi 90 seconds after boot, an AP will appear (RPi-Configure-WiFi)
2) Wait ~60 seconds before connecting to the AP
3) Connect to it with any device
4) A webpage should pop up (if not, try browsing the internet to force it to pop up)
5) Enter the desired WiFi credentials (**ensure they are correct**) and click the button
6) The Pi will now reboot and use these credentials.


### Dependencies 
The following packages are installed by `setup.sh`:
- hostapd
- dnsmasq
- nodejs
- npm
