Commmands 
1. systemctl list-unit-files --type=service
2. systemctl disable blueman-mechanism.service
3. systemctl disable bluetooth.service
4. apt install libspa-0.2-modules=0.3.19-4
5. apt install libspa-0.2-bluetooth
6. apt purge pulseaudio-module-bluetooth
7. apt install pulseaudio-module-bluetooth
8. reboot

After Reboot
1. systemctl enable blueman-mechanism.service
2. systemctl enable bluetooth.service
