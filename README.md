# Scripts
Random scripts I use exported in my PATH
They're probably not well built but they work for me

**bat_info**

Sends notification using `notify-send` with battery information. You may need to change the BATPATH.

**localssh**
+ Pulls Host infomration from `~/.ssh/config`
+ Display in a numbered list, when entering a number it will ssh into that system
+ 0 allows you to exit the loop

**update**
+ Updates/upgrades the following software

|Name|Description|
|:----------:|:-------------:|
|`paru`|Arch AUR/can be switched to `pacman`|
|`tldr`|Simplified man pages|
|`pip3`|Not currently in use|
|`fwupd`|Updates any firmware from [LVFS](https://fwupd.org/)|

+ Checks for known CPU vulnerabilities
+ Compares running kernel to latest, currently using `linux-zen` kernel. Then prompts for a restart if a newer kernel is available

**vpn**

Dependancies: ~~`wireguard-tools`~~ & `NetworkManager`
+ checks if current vpn interface is running
+ if running prompts to bring tunnel down
+ if not running prompts to bring tunnel up
