# NanoEDM

NanoEDM is an open source development precision EDM machine made from readily available components and existing machine shop tools. The nanoEDM has a quick change end effector mount allowing the user to easily swap between three types of EDM - wire, sinker, and fast hole. 

![Machine Front](https://github.com/alextreseder/picoEDM/blob/master/renders/PicoEDM_Machine_Front.png)

## Disclaimer

**EDM machines are dangerous**  
Beware electric shock and pinch points. Be prepared to activate emergency stop. Do not leave machine unattended. You are responsible for your own safety.

## Latest Version

Verison 12 adds the following features:
* Redesigned wire end effector
* Redesigned work table
* Switched water tank from plastic RV tank to stainless beer keg
* Added detail on XY motor mounts

[v12 CAD DOWNLOAD](https://github.com/alextreseder/picoEDM/blob/master/CAD/PicoEDMv58.step)

## Project Status
alpha

## Documentation
For documentation, please [**VISIT THE PROJECT WIKI**](https://github.com/alextreseder/nanoEDM/wiki).

## Concept
The current scope of the project: 
* Prioritze cheap solutions that don't sacrifice performance or features
* 530mm by 880mm footprint and 180mm XY travels
* Total machine weight < 200kg
* Use a magnetic particle break with a capstan wheel to tension the wire
* Use a custom but easily manufacturable pich roller to evacuate the wire
* Use stainless on ALL submerged fasteners and structure components
* Implement adjustable worktable for precision
* Water jet cut granite countertop machine base for thermal stability and rigid base
* Dielectric cooling solution from scrap refrigieration parts
* Use friction bar drive with dc brushed motors and linear scales for ultra precision
* Frame is designed to be liftable via forklift or pallet jack from either side
* Permanent tie down points in the frame's top corners
* High performance isolated power converter based spark generator with FPGA fast control loop
* Linux CNC build with attractive UI and integrated EDM process controls
* Fusion 360 post
* Support the following modifications:
  * Sinker EDM end effector
  * Hole popper end effector

## Future Goals
Future Development:
* Submerged rotary axis
* EDM grinding attachment
* Novel laser interferometer encoder system for performance and cost savings
* Novel low cost servo drives purpose built for the DC brushed motors + linear scales

## Non-Goals
This is not a minimal cost machine. The nano is meant to squeeze maximum performance and precision from a ~$3000 budget. Use of cnc machine and other machine tools considered acceptable for the DIY manufacture of the machine.
For a much lower cost and easier to build machine with some sacrafices, see my
[PICOEDM](https://github.com/alextreseder/picoEDM)

## Calculations
Desmos calculators have been made for various applications - they are not necessarily complete

[DESMOS - CAPSTAN EQUATION](https://www.desmos.com/calculator/trg4qsopa3)

#### Thanks:

See BAXEDM, one of the originals in the DIY EDM scene. This machine bears some visual similarities to his work, but in the finer details it is quite different. Mike Bax has built an amazing machine which inspired me to construct my own.
BAXEDM sells various EDM products poentially suitable for this machine. Check it out at 
[BAXEDM](https://www.baxedm.com/); 
[BAXEDM YOUTUBE](https://www.youtube.com/@baxedm9806)

README template inspired heavily by:
[CLOUGH42 ELS](https://github.com/clough42/electronic-leadscrew)
