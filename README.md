## SoC

SSC335 by SigmaStar <br><br>
Arch: ARM cortex-A7 <br>
Mem: 512Mb DDR2 <br>

![DSC00696](https://user-images.githubusercontent.com/36998819/152681576-1e04684b-a7b8-4dc9-9c55-9bfaa7e073ed.png)

<br>

---

<br>

## Storage

XMC QH64AHIG <br>
64Mb = 8MB <br>


![DSC00700](https://user-images.githubusercontent.com/36998819/152681872-2faf590b-a6b2-4c35-b9f8-497e388ab1ea.png)


---

<br>

## Wireless Controller

SSW101B by SigmaStar <br><br>


![DSC00702](https://user-images.githubusercontent.com/36998819/152682017-408dea18-2844-483b-9b05-e87b5a4d4cad.png)


---

<br>

## UART

UART pads are on the side of PCB facing backward (Although it's labeld TOP on the bottom right corner).

Baudrate: 115200

**The SoC used in C110 communicate over UART with 5V (Normally it would be 3.3V), so make sure you are using 5V compatible hardware or you may risk frying your equipment!!**


<br>

![UART](https://user-images.githubusercontent.com/36998819/152681555-e24a1b6e-8168-4a9a-b61c-d0038157fb8a.png)


<br>

The pads are on the edge of the PCB and seperated in 2.54mm pitch so it's perfect to solder pin connectors to it.<br>
Even so, the UART pads are still easy to be torn off so be careful while connecting/disconnecting!
<br>

![pin1](https://user-images.githubusercontent.com/36998819/152686720-be848940-3a73-47bc-be85-5673ac61154f.png)
![pin2](https://user-images.githubusercontent.com/36998819/152686730-97a2c47b-f19c-4f95-94d9-b0ce00d0a130.png)
