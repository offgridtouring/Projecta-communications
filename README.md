# Projecta-communications
Reverse engerineering the rs485 and canbus protocol for projecta battery management systems in caravans and rv
Gen 1
Display plug wiring
1) Red    - 12v
2) Yellow - RS485 B
3) White  - RS485 A
4) Black  - Ground
5) Blue.  - Can
6) Unused
7) Green  - Can
8) Unused

PMLCDC Cable - RJ45 (T568B)
1) Unused
2) Yellow    - 6) Green        - RS485 B
3) Unused
4) Unused
5) Unused     
6) Unused
7) White     - 3) Green/White  - RS485 A
8) Unused

PMCOMY Cable - RJ45 (T568B) (Shunt Plug)
1) Unused
2) Yellow    - 6) Green        - RS485 B
3) Blue      - 4) Blue	       - CAN L
4) Unused    - 2) Orange       - (Unsure - ON_OFF_OUT)
5) Unused    
6) Green     - 5)	Blue/white	 - CAN H
7) White     - 3) Green/White  - RS485 A
8) Unused    - 1) Orange/White - (Unsure - Gnd/Dry contact) 

PMCOMY Cable - RJ45 (T568B) (Sensor Plug)
1) Black     - 8) Brown        - GND
2) Yellow    - 6) Green        - RS485 B
3) Blue      - 4) Blue	       - CAN L
4) Unused    - 2) Orange       - (Unsure - ON_OFF_OUT - Wake up purpose)
5) Red       - 7) Brown/White  - 12v 
6) Green     - 5)	Blue/white	 - CAN H
7) White     - 3) Green/White  - RS485 A
8) Unused    - 1) Orange/White - (Unsure - Gnd/Dry contact - Wake up purpose) 
