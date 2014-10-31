Sun Fire V890 psu Pinout
========================

| 3,3V | 5V | 12V | 48V | 5VSB |
| --- | --- | --- | --- | --- |    
| 36A | 28A | 17.5A | 25A | 1,3A |

( Totals to 1.6 kW )


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
Example connection of the Powersupply to a Reprap Ramps Shield v1.4

* x3y3  ->  Ramps PS-ON
* x4y3  ->  x3y1
* x5y3  ->  Ramps VCC
* x6y3  ->  Ramps 5V

### V880 Notes: ###
I suspect (!) the Pinout for the v880 and v890 to be generally the same with the minor difference of 15 instead of 25 Amps at the 48 Volt Pin. (Which makes no big difference if you intend to power your Peprap Printer with it).
But it is substantially cheaper, you can get a v880 psu for ~ 20 Euro from Ebay.

Please drop me a line if you can verify that the pinout is indeed the same.
