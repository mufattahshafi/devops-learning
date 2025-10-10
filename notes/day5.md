DAY 5 : USERS,GROUPS and sudo

sudo adduser bob : add user name bob to system
sudo usermod -aG sudo bob : modify user to have access in group sudo (-aG = append group , without -a it would replace all groups)
getent group sudo : display information in group sudo , example which user have access to group sudo.

SWITCH USER :

sudo su - bob : this command will switch to user name bob

whoami : to check you login as which user


sudo visudo : edit the file for sudo group
