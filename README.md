## GRUB THEME  
The first is copy the folder 'GRUB_theme' to /boot/grub/themes/.  

## Edit the grub's config file  
Add the following line to /etc/default/grub  
GRUB_THEME="/boot/grub/themes/GRUB_theme/theme.txt"  
For example:`sudo vim /etc/default/grub`  

## Update grub.cfg  
For example:`sudo grub-mkconfig -o /boot/grub/grub.cfg`  

If everything is OK, you will see the following line:  
Found theme: /boot/grub/themes/GRUB_theme/theme.txt  

### Reboot and you will se our new grub theme  
