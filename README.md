sun-fire-v890-psu-pinout
========================





| OFF |     |     |     |     |  B1 |     | Pins |  x1  |  x2  | x3  |  x4  |  x5  |  x6  |     | A1  |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     |     |  y1  |   0 | GND |   0 | 4.8 |  0  | 6.05|     |     |     |     |
|     | 0   | 0 | 0 | 0 | GND |     |  y2  | 4.93|   0 | GND |   0 |0.03 |    0|     | GND | GND | 0  |
|     |     |     |     |     |     |     |  y3  | GND |   0 | 4.84| GND |5.11 | 5.11|     |     |     |     |
|     |     |     |     |     |     |     |  y4  |   0 |   0 | 0.06| 0.7 | GND | 0   |     |     |     |     |


To start the Power Supply shorten Pins x4y1 to GND and x3y3 to GND.


| ON |     |     |     |     |  B1 |     | Pins |  x1  |  x2  |  x3  |  x4  |  x5  |  x6  |     | A1  |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     |     |  y1  |   0 | GND |   0 | 0 |  0  | 6.05|     |     |     |     |
|     | 12.1   | 5.1 | 3.4 | 3.4 | GND |     |  y2  | 4.93|   0 | GND |   0 |0.03 |    0|     | GND | GND | 48.1  |
|     |     |     |     |     |     |     |  y3  | GND |   3.37 | 0| GND |5.11 | 5.11|     |     |     |     |
|     |     |     |     |     |     |     |  y4  |   0 |   0.15 | 0.06| 0.7 | GND | 5.14   |     |     |     |     |


### Reprap Ramps ###
Connection of the Powersupply to your Reprap Ramps Shield

* x3y3  ->  Ramps PS-ON
* x4y3  ->  x3y1
* x5y3  ->  Ramps VCC
* x6y3  ->  Ramps 5V


