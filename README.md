# Linear-Sega-Saturn-Power-Supply
<br>
A super clean Sega Saturn PSU for VA-SG  / VA-SD mainboards found in rev2 (white) Saturns.
<br>
<br>

## Table Of Contents

<br>

[Components](#Components) <br>
[Usage](#Usage) <br>
[Description](#Description) <br>
[Installs](#Installs) <br>
[Compatibility](#Compatibility) <br>

<br>
<br>
      
## Components
<br>

![alt text](/images/H0669.jpg) <br>
H0669 Heatsink<br>
<br>
<br>

![alt text](/images/PowerConnector.jpg) <br>
Generic 2.1mm Bulkhead Male DC Power Connector <br>
I had someone custom print me the plastic mounting part for fitment into the saturn
<br>
<br>

![alt text](/images/PowerSwitchConnector.jpg) <br>
digikey P/N A106608-ND (or re-use the one off the factory PSU) <br>
<br>
<br>

![alt text](/images/Molex.jpg) <br>
Mouser P/N 09-48--4059 (or re-use the one off the factory PSU) <br>
<br>
<br>

Diode * 1

* 1N5822 Schottky 40V 3A DO-27

Regulators

* Texas Instruments LM1084IT-5.0
* Microchip MIC2940A-3.3WU LDOI 3.3v / 3-Pin, D2PAK (TO-263)

Capacitors (Go high quality! Wurth, kemet etc. )

* Input (shared): 100uf 35v
* Smoothing: 220uf 25v * 2
* High Freq filter: 0.1uf 50v * 2
<br>
<br>

Power Supply

* Any high quality 9v supply, at least 2A output. I use the M8925D, but others will suffice.
      
## Usage
<br>

* This is a replica of the factory PSU in regards to the PCB shape. It will fit like a factory supply and the heatsink clears the top shell.<br>
<br>

* The jumper is for users wanting to use the disc drive rather than an ODE. It's a safety guard because you might be using a 12v supply.
This is not recommended, it generates more heat for the linear regulators to dissapate. The 3.3v reg usually won't even  get luke warm but the 5v regulator
will however generate needless heat.  Second to this, the disc drive wants the 9v supply to operate. I wouldn't risk running it at 12v, it probably has it's
own step down regulator but its run at 9v from factory. The DIODE will drop the 9v input down to about 8.5v to 8.6v. The disc drive circuit is happy with this.
<br>
<br>

## Description

I've sold quite a few pre-modded systems with these, and the supplies on their own. 100% happy customers. I will continue to sell them but decided to open source the project. It's a simple design, it works well, you won't find a cleaner supply. This was tested under the scope. It is quite literally, on average, about 10x cleaner than the switching supplies out there. I added the CD drive track/ jumper before uploading the design as I've had to instruct a few people on how to run a bodge wire. The saturn documents out there won't tell you that you need that line, but it definitely operates the disc drive on these particular revisions of board.

## Installs

![alt text](/images/1.jpg) <br>
With original fenrir ODE (Before the 20/21pin became a single board) <br>
<br>
<br>

![alt text](/images/2.jpg) <br>
With original fenrir ODE (Before the 20/21pin became a single board) <br>
<br>
<br>

![alt text](/images/3.jpg) <br>
Custom fully recapped saturn with clear shell,  FRAM and MODE ODE, utilising the external 5v pads on the PSU to power the MODE<br>
<br>
<br>

## Compatibility

![alt text](/images/compatible.png)

