# Install Arduino IDE and CH340 driver
### Installing Arduino IDE a

1. https://www.arduino.cc/en/main/software 
2. (Linux)Using the command line 
``` bash 
sudo apt install arduino 
```
3. CH340 Driver: https://sparks.gogo.co.nz/ch340.html (Make sure the arduino uno is connected when installing the driver)
4. Tools -> Board -> Arduino Uno 
5. Tools -> PORT -> COM4 (May be different, for windows check device manager -> COMM & LP -> USB-SERIAL CH340 (COM?)
# LG01-N Gateway 
Things you will need: LG01-N and RJ45 cable

1. Configure LG01-N for internet connection 






## Julian Grado's Setting Up LoRa 

My History Process with the LORA:
 - I received the package continuing the LORA Kit. 
 - I brought it into my room and began opening each item
 - Each group of items was photographed 
 - Each photograph was given to Ramiro Gonzalez
I began to look on youtube on how to program and assemble the kit, sadly no luck.
I went on the Draginuo website and found the user manual and began to program and assemble based off of the steps and images. 
The kit required at the start Arduino and a drivers download so the computer can detect when an item from the kit is connected wirelessly or through the USB port. 
I have a mac and finding how to download the drivers software was difficult. 
I found this website with a video and preexisting commands for my terminal so i can download and install
It didn't do anything, I tried it twice, and my computer still wasn't picking it up
I asked my team for some help and I had to wait a couple days until they figured it out. 
Armaan found this website that didn't need the terminal, and I downloaded it. 
The driver worked and my computer could detect the devices from the kit 
Next on the instructions we moved to making a gateway. 
This involved connecting to the LGO-1 N network and using the http://10.130.1.1/cgi-bin/luci/admin link 
I needed to scan for my home internet connection and connect it. 
I had to disable the previous LGO-1 N connection
Once i tried to connect to my home internet, my LGO-1 N crashed and said it failed to back up
I tired to stop it from doing that bty redoing the steps multiple times but it kept crashing
It disconnected me from the LGO-1N and kept connecting to my internet, this was supposed to happen but at a later step. 
It kept asking me to do “ add the next back up” , so I did think it would change the outcome, but by doing so it just made my LGO-1N undetectable and now I can’t connect to it. 
THat is where i am now, stuck on step ⅘  on the instructions on making a gateway. 
