#LinuxSystem GRUB2 Theme
#Based on the theme Arch-Silence 
#Created in 2015 by LuizFNunes 

# To install the theme:
# 1 - copy the folder linux-system to /boot/grub/theme/

sudo cp -R linux-sytem/ /boot/grub/theme

# 2 - add or modify the next line in the file /etc/default/grub:

GRUB_THEME="/boot/grub/theme/linux-system/theme.txt"

# 3 - Update the configurations:

sudo update-grub

# Supported Resolutions

800   x 600
1024  x 768
10366 x 768
