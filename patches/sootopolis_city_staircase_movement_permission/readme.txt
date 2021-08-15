Fixed the movement permission for the tile to the left of a staircase in the north-east of Sootopolis City.
A detailed explanation can be seen here: 

Either patch via the .ups file or simply flip the byte at offset 0x28E375: 02 -> 06
Works only on Ruby and Sapphire!