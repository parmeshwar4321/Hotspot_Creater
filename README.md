# Hotspot-Creater (for linux users only) 

## first of all check your wife interface
#### open your terminal and type following command.

```
user@user-laptop_name:~$ iwconfig
```
## if your wife interface is wlp3s0 then type following command


```
user@user-laptop_name:~$ sudo apt-get install hostapd git build-essential
```
## after that clone following  repositery in your system

```
user@user-laptop_name:~$ git clone https://github.com/oblique/create_ap.git
```
## change your current directory to directory where you clone above repositery and install it.
```
user@user-laptop_name:~$ cd create_ap
user@user-laptop_name:~$ sudo make install
```

#to enable your hotspot 
```
user@user-laptop_name:~$ sudo create_ap wlp3s0 wlp3s0
ssid:typeyourssid
passphrse:enter your password
retype passphrese: enter again your password
```
