Piezometer_Monitoring
=====================
CRBasic scripts for CR1000 Data Logger to record measurements from a<br>
Geokon 4500HD Piezometer and Global Water ultra-sonic water level sensors.

CR1000 Wiring
-------------
**Instruments:**<br>
  <li>Geokon 4500HD Piezometer with Armored Cable</li>
  <li>Global Water WL705-048 Ultra sonic water level sensor</li>
  <li>Global Water WL705-012 Ultra sonic water level sensor</li>
**Campbell logger components:**<br>

  1x CR1000 Data Logger<br>
  1x DCDC18R Voltage Booster (12V->18V)<br>
  2x CURS100<br>
  1x AVW200 Vibrating Wire Converter<br>
  1x CFM100 CF card reader w/ 1 CF card<br>
  1x DB9M to PIGTAIL/STRIP AND TIN 2ft cable<br>


| RS-232 Wire | CR1000 Terminal | Description |
|-------------| :------------:  | :---------: |
| Brown | **C1** | COM1 **Tx** |
| White | **C2** | COM1 **Rx** |
| Yellow | **G** | Ground |

**note:** *colors may vary depening on  the DB9M to Pigtail you use*


**Wiring for Global Water ultrasonic water level sensors**


| **WL705-048** | Color | Instrument | Terminal |
| ----- | ----- | ---------- | -------- |
| Power | Red   | DCDC18R | **V<sub>out</sub>+** |
| Output | White | CURS100 | **H** |
| Ground | Black | CURS100 | **GND** |
| **WL705-012** |  | | |
| Power | Brown | CR1000 | **V<sub>out</sub>+** | 
| Output | Black | CURS100 | **H** |
| Ground | Blue | CURS100 | **GND** |

**L** *terminals of the CURS100 are connected to logger Ground terminals*

