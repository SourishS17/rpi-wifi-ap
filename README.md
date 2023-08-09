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
- Within 3 minutes of boot, if no WiFi is connected, an AP will appear (RPi-Cofigure-WiFi)
- Connect to it with any device
- A webpage should pop up (if not, try browsing the internet to force it to pop up)
- Enter the desired WiFi credentials (**ensure they are correct**) and click the button
- The Pi will now reboot and use these credentials.


### Dependencies 
The following packages are installed by `setup.sh`:
- hostapd
- dnsmasq
- nodejs
- npm
