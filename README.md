# homemgr
 Manager of home directories in Linux. 

## Screenshot:
![Image of Screenshot_5](http://beeimg.com/images/h70212054903.png)

## How-to use:

**homemgr -h**

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
