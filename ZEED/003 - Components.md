These are the individual components required to make the system function as a whole;

-Firmware (Runs all the rules. Generally shouldn't be changed by the enduser.)

-Egg Protocol (Firmware rule that controls the first stage of .zeed life)

-First Hatching Protocol (Need to find out what of the 7 available bytes of NFC data can be programmed to do what, and why. Must retain some data that cannot be user edited (ie. first byte always has to be 0001) so that Protocols are Az-Distributed only (with some user-creation of rules possible)

-Public Hatching Protocol (First release NFC data that everyone uses at the start.)

-Combat Protocol (Controls how combat using hardware and wireless interfaces function. ie. When does hp go down, what is damge, etc)

-Training Data Functions (Copy pwnagotchi here)

-HASH (Firmware rule that controls food and DEX correlation to BIN, visible to enduser as a digit or string)

-Bitrate (Misnomer, actually Bit Rot. Simple equation in firmware to randomly flip bits in BIN over time. Should be able to be changed dynamically by .zeed on SD. Not visible to user)

-Rules (Kept on an SD and integrated in a .zeed via BIN as dictated by firmware. 'Firmware Rules' are kept in firmware only, not on SD)

-.zeed (Just a hexadecimal file, sorta. Maybe an uneditable header?)

-Protocols (a type of Rule applied to .zeed to control how it lives its life)

-PGP Functions (No idea how to do any of this. Could add it to egg protocol or something)

-Mail (Az-run server)

-GRID (Az-run server)

-Combat System (User-Run Server)

-Editor & Viewer Program (Client App; Android, WIN, LIN, MAC. Connects to Mail, GRID and Combat System Servers. Pulls data off device for use)
