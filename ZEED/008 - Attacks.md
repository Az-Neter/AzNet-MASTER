Combat between two or more .zeed takes place with each sending 'Attacks' to the other in order to try and alter their data.  

Combat takes place on a grid where each .zeed can:  
-change its own location  
-link a target or ally  
-send attacks toward their target  
-send attacks toward attacks targeting allies  
-change frequency  
-defend  

The overall rate at which attacks are transmitted is determined by the server Tick Rate.  
The rate at which a .zeed can perform actions in sequence is mostly determined by its DEX stat.
  
  
Types of Attacks:

Infrared - Overwhelms Visuals  
Auditory - Overwhelms Speakers

Physical - Direct Attack. Flips bits.  
Sub-Ghz - Wireless Attack. Flips bits.

Data Drain - Sends 0s  
Data Overload - Sends 1s

Equation - Read Below
    
  
Physical bit flips attacks are A vs B vs C against enemy Defend.  
Bit flips are identified visually by their symbol (Circle for A, Triangle for B, Square for C)
The rate you can set your Defend as well as the rate your attacks go out is determined by DEX.

Wireless bit flip attacks (sub-Ghz) operate on a frequency range and can be defended against by altering your own frequency.  
The rate you can change your frequency for attacking or defending is determined by DEX.

Data Overload and Data Drain are counterparts to oneanother.  
A Drain can defend against an Overload mid-battlefield and vice versa by cancelling eachother out upon impact.

IR and Audio attacks primarily affect the user, not the .zeed

Equations are complex attack and defense sequences run as a single command and applied at the same time.  
They are installed from RFID or Scripts as Equipment and their contents can be seen by everyone in the battle as it's used.  
Usage speed is determined by DEX value.   
The amount of Equations you can have installed is limited by your .zeed's Stage;  
ROOT - 0  
CORE - 1  
BETA - 2  
APEX - 5  

Every 1 in the .zeed's BIN is a single point of HP.  
If no more bits remain, the entity can no longer exist.  
Utilizes the hexadecimal values of the BIN to determine what attacks can and cannot be used  
(ie. an A5 byte in the binary means you can use Audio attack. Note 'hex value of BIN' is NOT 'HEX' as described in definitions {the user-editable .zeed file}, but instead refers to the actual BIN, which is diplayed as binary digits.  
That means even 0s are used when calculating the 'hex of BIN' for deciding attacks, whereas the HEX is just pure user-editable hexadecimal which doesn't ac count for all 0's displayed on screen.
