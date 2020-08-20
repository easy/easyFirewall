# easyFirewall
![GitHub](https://img.shields.io/github/license/easy/easyFirewall)
![GitHub repo size](https://img.shields.io/github/repo-size/easy/easyFirewall)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/easy/easyFirewall)
![platform](https://img.shields.io/badge/platform-debian%208%2C%209%2C%2010-brightgreen)

## What does the script do?
- DDOS Protection
- Whitelist- & Blacklist-System

## How to install?
Go with ```cd``` to the root directory of your debian server and execute this command:
```
wget https://github.com/easy/easyFirewall/easyFirewall.sh && chmod +x easyFirewall.sh
```

## How do I execute the script?
Anytime you want to start the script, you have to go to the root directory with ```cd``` and execute this command:
```
./easyFirewall.sh
```

## First execution
1. The first time you install the script, the following packages are downloaded and installed / updated for the script to work:
- packages soon
2. Then the script asks you if you accept the license. You have to confirm this with ```1```.
3. Last but not least, the script automatically updates to the latest version, if it is not yet up to date.
4. Now you are in the "panel", in which you will be redirected immediately if the script is executed again. (Without package installation and license confirmation)

## The "panel"
### IMAGES SOON
Generally you navigate in the "panel" by entering numbers. Sometimes it is possible to specify strings instead of digits.

## Settings
The settings can be changed in the panel under Settings. The following setting options are given:
- Layout
- automatic updates / manual update

## API
These commands can be used as an interface:
- ./easyFirewall.sh start - start the firewall
- ./easyFirewall.sh stop - stop the firewall
- ./easyFirewall.sh status - show the current status of the firewall

Important: The commands must always be executed in the root directory.

## To-Do
[ ] Restore firewall status on startup

## Bugs and mistakes
It always happens that mistakes are made and bugs occur. I ask you to point this out to me or if you want to even improve it. :)
