# Philips-MCM206-IR-remote
List of RC5 signals used by the Philips MCM206 to communicate with an infra-red remote.

This list was simply build with an arduino and the IRremote library (https://github.com/z3t0/Arduino-IRremote).

| Command | RC5 12-bit |  data |  rawData | 
|:-:|:-:|:-:|:-:|
| **Power On**  |  40D | 0x40D  |  1100,650, 1800,1700, 1800,850, 1100,650, 900,850, 900,850, 900,850, 1100,1550, 1100,650, 1800,1700, 950 | 
|  **Power Off**  |   |   |   |  
|  **Blank**  |   |   |   | 

