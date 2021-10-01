# QARCH
Simulators for the Q15 architecture

**QARCH**: Fully featured shell based simulator for Q15 for use on Linux/Unix systems.

To initialize:

`mount -t tmpfs -o size=150M QARCH /path/to/QARCH/working/directory`

`cd /path/to/QARCH/working/directory`

`tar xJvf /path/to/QARCH/archive.txz`

`cd ./Q15`

`./VTLBankGen 2&> /dev/null`

You now have a copy of QARCH ready to be programmed. To shutdown (deletes all data not read into ROM on cleanup!) `./Shutdown`
All boot time operations need to be directly added to VTLBankGen, or scripted into ROM and called during the ROM loading phase of VTLBankGen

**Compublop**: Slowly evolving proof of concept circuit schematic for Q15's MemBanks memory system. Minecraft MAP format, fully operable.
