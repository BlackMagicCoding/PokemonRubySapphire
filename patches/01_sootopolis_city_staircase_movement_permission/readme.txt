Fixed the movement permission for the tile to the left of a staircase in the north-east of Sootopolis City.
A detailed explanation can be seen here: 

Either patch via the according .ups file or simply flip the byte at the following offsets from 0x02 to 0x06:
Ruby		0x28E375
Sapphire	0x28E305
Emerald		(has been already fixed)