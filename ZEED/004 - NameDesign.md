Potential options for how to generate the Name of a .zeed

-Option One:  
Take the First character of the Hatching Protocol (from SAQ of the NFC, half of one byte in hex)  
Combine with the first byte of hex taken from a hatched .zeed   
(would have to retroactively rename the file, could start with egg.zeed instead of writing new data from firmware. Allows for special eggs later)  

Example:  
NFC Test Protocol = FF (SAQ) - FF FF (ATQA) - FF FF FF FF (UUID)  
Hatched .zeed =   
01 01  
01 01  

Filename = F01.zeed



-Option Two:  
Hex or Binary to ASCII converter run on hatched .zeed
