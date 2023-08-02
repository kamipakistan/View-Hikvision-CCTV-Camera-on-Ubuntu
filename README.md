# How to View Hikvision CCTV Camera on Ubuntu Using Firefox Web Browser

## 1. Install Wine 7 on Ubuntu 20.04.4 LTS
## 2. View Hikvision CCTV Camera on Ubuntu Using Firefox Web

### 1. Steps to Install Wine on Ubuntu 20.04.4 LTS
* I. Enable 32-bit architecture support
  ```
  sudo dpkg --add-architecture i386
  ```
* II. Check architecture using the following command
  ```
  dpkg --print-foreign-architectures
  ```
* III. type some description about the following command here
```
wget -nc https://dl.winehq.org/wine-builds/winehq.key
```
* IV. type some description about the following command here
```
sudo apt-key add winehq.key
```
* V. type some description about the following command here
```
sudo add-apt-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ focal main'
```
* VI.type some description about the following command here 
```
sudo apt update
```
* VII. Install Wine on Ubuntu
```
sudo apt install --install-recommends winehq-stable
```
* IX. Check Wine Version
```
wine --version
```
* X. After wine installation reboot your system.
```
sudo reboot
```

## 2. View Hikvision CCTV Camera on Ubuntu Using Firefox Web
