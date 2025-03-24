Files start with the header in the following bytes
42 72 69 67 6D 61 70 66 69 6C 65
Then the version number is specified as a hex byte eg
01
then there are for bytes that abriviate the game that the map is for in hexadecimal conversion eg
thwa translated to 74 68 77 61

the data is all just objects each object starts with 2 bytes for the hex number that is equal to the number of the object to be loaded eg
00 01 for 1
and 00 b0 for 11
