# Klipper-for-TronXY-X5SA-STM446-mainboard
A simple guide for installing Klipper on your TronXY X5SA with an STM32F446 chip

# Required hardware:
- Pi/computer running Pi OS Lite or any other debian branch
- Usb cable to connect to the printer
- 32GB or less sd card, I used the 8GB card that came with the printer

m# Installing Klipper onto the Pi/ Linux computer using KIAUH
Check out the KIAUH repo for more detailed instructions: https://github.com/th33xitus/kiauh

SSH into your Pi or other computer and run
```
sudo apt install git 

cd ~

git clone https://github.com/th33xitus/kiauh.git

./kiauh/kiauh.sh
```
After you run all of those, your terminal should look similar to this:

![](pictures/kiauh1stpanel.png)

Next, type in "1" to get to the install page.

![](pictures/kiauh2ndpanel.png)

Install Klipper, Moonraker, and Mainsail or Fluidd