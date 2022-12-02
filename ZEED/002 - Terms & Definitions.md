ZEED = The entire project, the extension of the main user-editable file, the name of the 'egg' form of the entity's Stage

Stage = A controlled evolution of existing data. Stages include: ZEED, ROOT, CORE, BETA, APEX, and XROS (last entry name WiP)

Level = Combat experience gained by a .zeed

Training = Lightweight neural net built from training data. Training data is gained from 'Training Mode' where data is learned via user interaction and used during normal operation

Safe Mode = Function to lock all wireless capabilities to prevent training data from getting user in trouble with the Law

Combat System (Name WiP) = A user-run server which allows multiple .zeed to connect and gain levels through pvp or pve interactions. Addon to GRID.

Chat = Local p2p Sub-Ghz, IR and NFC wireless hardware interface system to share text data and user contact information

(Hatching) Protocols = NFC-A tag consisting of SAQ (1 byte), ATQA (2 byte) and UUID (4 byte) in Hexadecimal, used to dictate how a .zeed functions at its core level while in every stage beside ZEED

Memory NFC = The actual physical (or emulated) tag that holds a Protocol.

Name = Set by .zeed on hatch. Permanent and unchangeable. Uses Protocol to create. Should be mostly unique even with different protocols.

Name.zeed = The entity itself. User-editable hexadecimal file with some uneditable parts (corrupts if edited). Contains all info about a .zeed besides it's Level

HEX = the actual user-editable Hex code shown to the enduser (via info about your zeed and companion editor program)

BIN = what the HEX looks like as a creature. Rules from Protocols and raw data from HASH are applied to the BIN to determine movement and interaction capabilities. 1's in BIN are equivalent to HP points

Bit Rot = Set by 'Bitrate' within the firmware. Randomly decays 1's in BIN into 0's at a set rate. Possible future functions

Food = Raw data. Can be anything, from pictures to text to HEX and everything in between, as long as it's small enough.

HASH = 'Weight' stat of entity. Increases when raw data (Food) is input. Correlates to DEX

DEX = Dexterity / Speed of the entity. Determines how 'intelligently' it can access its training data and how fast it attacks, defends or evades in combat

Key = a pgp key assigned to the .zeed. Private key should not be accessible to the user, and pub key used for all mail and chat functions. Not used for file encryption

Mail = Internet-based .zeed-to-.zeed user communication. Integrates with Combat System & GRID

GRID = Internet-based Az:Net-run game server (cloneable) in which users can upload their .zeed and interact in a pvpve coding and cyberwar playground. .zeed not required.

