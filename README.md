# Termux-boot
Executes all scripts in /data/data/com.termux/files/home/boot in separate termux-sessions, 5 minutes after boot. 

This code requires being rooted. 
For this to work the code in the boot-termux file must run on boot. If you have magisk, you can place the boot-termux script in /magisk/.core/service.d. Otherwise you will have to find out if any init scripts in the /etc directory of your phone are executed on boot, and append the boot-termux code to that. 

The termux-url-opener file must be placed in ~/bin/termux-url-opener (use chmod +x to make it executable). 
If you are already using termux-url-opener rename it to termux-url-opener-2 and all links that do not begin with TermuxLauncher.xyz will be redirected to it. 


