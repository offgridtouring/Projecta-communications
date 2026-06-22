Projecta Gen 3 System Decoder (Master List)

Byte 0 - Start Delimiter
Alerts all nodes on the bus that a valid packet is starting.
7E - Alerts all nodes on the bus that a valid packet is starting.

Byte 1 - Source ID
Identifies which physical device sent the message.
FO - Display

Byte 2 - Destination ID
Specifies who the message is for
FF - Broadcast (Everyone)
80 - PM535

Byte 3 - Function Code
Modbus-style command type.
03 - Read Holding Registers

Byte 4 - Sub-Function
Directs the command to a specific internal hardware profile or subsystem.

Byte 5 - Total Package length
The Magic Byte. Dictates the absolute byte length of the entire packet from the 7E header to the final CRC.
0C (12 bytes total)

Byte 6> - Data Payload

Last 2 Bytes - CRC Checksum
16-bit Modbus standard verification token to confirm the packet isn't corrupted
