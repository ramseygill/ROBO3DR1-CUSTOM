# ROBO3DR1-CUSTOM
Custom Marlin firmare for a heavily modified ROBO 3D R1 3D printer.

### NOTES
* Flashed to Arduino Mega 2560 (RAMPS) with Arduino IDE 1.0.6
* RepRapDiscount Full Graphic Smart Controller requires specific U8glib library to be installed. This gave me some grief so I included it as a .zip file. https://github.com/olikraus/u8glib/wiki 

### List of Modifications 
- Replaced stock Hexagon hot end with E3D V6, altered thermocouple type
- Replaced heated bed https://hackaday.io/project/161487-upgrade-robo3d-r1-heated-bed-100w altered thermocouple type.
- Tuned PID loops for hot end and heated bed.
- Added RepRapDiscount Full Graphic Smart Controller https://reprap.org/wiki/RepRapDiscount_Full_Graphic_Smart_Controller
-  Followed Toms guide https://www.youtube.com/watch?v=H3wj9l1hvVw
-  Encoder direction fix https://youtu.be/H3wj9l1hvVw?t=231
-  Encoder Scolling increments fix https://youtu.be/H3wj9l1hvVw?t=231
- Raised max temps for hot end (295) and bed (120). 
- Changed printer's cosmetic name to "RISKY3D R1" 

