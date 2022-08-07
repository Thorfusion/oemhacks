# Modifying DELL PRECISION T3600 to work with sztandard computerparts

# PSU PINOUT
The connectors itself are MOLEX Mini-Fit Jr

Note that pin 3 and 4 are the same 12V rail as the 10 and 11 on a regular 24 pin. Pin 10, 11 and 20 is the rail for sata and etc.
![](https://raw.githubusercontent.com/Thorfusion/oemhacks/main/dell/precision/t3600/psu-pinout.png)

## PSU CABLE DIAGRAM
![](https://raw.githubusercontent.com/Thorfusion/oemhacks/main/dell/precision/t3600/dell_24_pin.png)

# FRONT IO
Front io connectors itself are MOLEX Milli-Grid

Alot of people has been using the remote control port to turn on their computers and etc. I'm gladly to announce that i reverse engineered the front io just for other to use.

## PINOUT
![](https://raw.githubusercontent.com/Thorfusion/oemhacks/main/dell/precision/t3600/io_pinout.png)

## Front IO diagram
NOTE: This does not contain front audio since its just pin to pin as previos image shows.
![](https://raw.githubusercontent.com/Thorfusion/oemhacks/main/dell/precision/t3600/front_io.png)

# DELL FAN PINOUT
The connectors itself are called MOLEX SL Modular Connectors

## DELL 4 PIN

### PIN
1. 
2. 
3. 
4. 

## DELL 5 PINOUT
### PIN
1. RPM
2. 12V
3. GND
4. PWM
5. 

### The ILM mount is an industrial troughhole and needs to be changed.
You can fit this motherboard fairly easely in another chassy with some modifications. new mount holes need to be drilled and a cut on the io hole needs to be made.

heres a website explaining of swithing the mount ilm for coolers
https://www.overclock.net/threads/my-dell-heatsink-adventure.1635648/
