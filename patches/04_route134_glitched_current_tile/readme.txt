Fixed the movement permission for the tile in Route 134 where you can walk onto the current.
A detailed explanation can be seen here: https://youtu.be/ZM53HYAYGsY

Either patch via the according .ips file or simply flip the byte at the following offsets from 0x32 to 0x12:
Ruby		0x2C4D1B
Sapphire	0x2C4CAB
Emerald		0x41DAE3