ArcadeTable  
-----------  

# Links
## General  
https://www.instructables.com/RetroPie-Arcade-Cabinet-Cocktail-Style/  
https://www.mamedev.org/  

## Shopping  
### Buttons, sticks ETC PACK;
**$88 walmart** https://www.walmart.ca/en/ip/LED-Arcade-Buttons-Set-2-Player-Arcade-DIY-Way-Joystick-Kit-Player-Arcade-DIY-Kit-Performance-Driven/PRD2SD0VHDIATF9   
**64.88 Amazon** https://www.amazon.ca/Hikig-Buttons-joysticks-Controller-Raspberry/dp/B07JFXQSM5  
**$81 Amazon** https://www.amazon.ca/Hikig-Updated-Version-2-Player-Arcade/dp/B07WGK99X5  
**$31 Aliexpress** https://www.aliexpress.com/item/1005004379566897.html  
**$31 Aliexpress** https://www.aliexpress.com/item/1005003980453193.html  





# RetroPi setup   
**Ip address**: 10.0.0.63 SSH enabled, static ip address       
**Username**: pi  
**Password**: raspberry    


# Issues
## Installing Linux   
### No network connection (Wired & Wireless)
For some reason the network wasn't working during install, or even afterwards (without package-manager due to network issue).   
**Solution:** Install debian with graphical userface on the ISO (DVD ISO install from debian website).     

## Installing RetroPie   
### Cannot locate packages  
1) Remove cd-rom from the list of packages and restore the default by running `sudo cp /usr/share/doc/apt/examples/sources.list /etc/apt/sources.list`.
2) `apt-get install upgrade`, `apt-get install update`.
3) Now you can run `apt-get install git` and follow the steps: `https://github.com/RetroPie/RetroPie-Docs/blob/master/docs/Debian.md`. **Note: you can skip the `sudo apt install -y git dialog unzip xmlstarlet` step **
