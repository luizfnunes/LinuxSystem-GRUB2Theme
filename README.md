# LinuxSystem

LinuxSystem GRUB2 Theme<br/>
Based on the theme Arch-Silence<br/> 
Created in 2015 by LuizFNunes <br/>

<h3>Install</h3>

1 - copy the folder linux-system to /boot/grub/theme/
```Shell
sudo cp -R linux-sytem/ /boot/grub/theme
```

2 - add or modify the next line in the file /etc/default/grub:
```Shell
GRUB_THEME="/boot/grub/theme/linux-system/theme.txt"
```

3 - Update the configurations:
```Shell
sudo update-grub
```

<h3>Supported Resolutions</h3>

800   x 600
1024  x 768
10366 x 768
