# PhoneSploit
A tool for remote ADB exploitation in Python2.

# Features
* Access Shell
* Screen record victim device
* Screenshot a picture on victim device
* Pull folders from victim device
* Turn victim device off
* Uninstall an app
* Show real time log of victim device
* Dump system info
* List all apps on victim
* Run an app
* Port Forwarding
* NetStat
* Grab wpa_supplicant
* Turn WiFi On/Off
* Show Mac/Inet
* __Remove Password__
* Extract apk from app  
* Use Keycode   
* Get Battery Status
* Get Current Activity

#Credits
<br> Original code by https://github.com/metachar/PhoneSploit
<br>

# PhoneSploit 



Using open Adb ports we can exploit a device
<br> you can find open ports here https://www.shodan.io/search?query=android+debug+bridge+product%3A”Android+Debug+Bridge”
<br>



# HOW TO INSTALL ON WINDOWS
```
git clone https://github.com/cyb3rt3ch/PhoneSploit
extract adb.rar to the phonesploit directory 
cd PhoneSploit
pip install colorama
main.py
```

# HOW TO INSTALL ON Linux
```
git clone https://github.com/cyb3rt3ch/PhoneSploit
cd PhoneSploit
pip install colorama
python2 main_linux.py
```

# HOW TO INSTALL ON macOS
First of all, install [brew](https://brew.sh)
```
brew install git python@2
git clone https://github.com/cyb3rt3ch/PhoneSploit
cd PhoneSploit
python2 -m pip install colorama
python2 main_linux.py
```

# IF ADB NOT FOUND
```shell
sudo apt update

sudo apt install android-tools-adb android-tools-fastboot

```


