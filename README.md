# Zenith

Zenith is a small single board computer made with the RK3328 which comes with 512 MegaBytes of DDR3 RAM. Zenith is built to run on battery backups along with USB Type-C power inputs. Features of zenith are:  

- Quad core ARM Cortex-A53 CPU
- 512 MB DDR3 RAM
- SD support
- 100M ethernet
- HDMI out
- 24 bit audio
- 1x USB 3.0 2x USB 2.0

I made this SBC because i wanted to locally host some slack bots. There is literally no other reason. I have not compiled buildroot because 

Check out this project on [KiCanvas](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FKeyaan-07%2FZenith%2Ftree%2Fmain%2Fhardware)
To check schematics, please go to the above link, imaging every page and putting it here would clutter the README.


![kicad-pcb](/media/render.png)
![kicad-render](/media/3d-kicad.png)
![kicad-render-back](/media/3d-kicad-back.png)
![kicad](/media/pcb.png)


# Assembly guide:  
1. clone the repo and head to production: 
```bash
git clone https://Github.com/Keyaan-07/Zenith
cd Zenith/hardware/production
```
2. go to your preferred PCB manufacturer and upload the gerber files there. 
3. get the PCBA option for both(or one) sides.
4. Build the firmware from the [buildroot](https://github.com/buildroot/buildroot) repo.
5. flash it to the SD card using [rufus.ie](https://rufus.ie)
6. plug the SD card in and start the board. 




# BOM
