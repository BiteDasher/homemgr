# homemgr
 Manager of home directories in Linux. 

## Screenshot:
![Image of Screenshot_5](http://beeimg.com/images/h70212054903.png)

## How-to use:

**homemgr -h**

# Dependencies:
```bash``` - of course \
```coreutils``` - basic commands \
```libc``` - getent command **(optional, for native getent command)** \
```sed``` - parsing \
```shadow``` - add/modify/remove groups/users for import \
```tar``` - archiving home directory

# Exit codes:
1 - invalid argument(s) \
2 - scipt executed not as root \
3 - user not exists \
4 - something wrong with home directory of user \
5 - UID is lower than 1000 \
6 - useradd / usermod / userdel / groupadd / tar error \
7 - home directory is not contolled by homemgr \
8 - Invalid path \
9 - something not found \
10 - home directory doesn't exists \
11 - configuration file of user is broken

# AUR git clone link:
https://aur.archlinux.org/homemgr.git

### If you are upgrading from version <=1.3 to >=1.4
Do not forget to do ```homemgr -u USERNAME``` after the upgrade

### If you are upgrading from version <=1.6 to >=1.7
Enter ```sudo FIX_ATTRS=1 homemgr```
