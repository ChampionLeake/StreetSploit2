# StreetSploit2 (FIFA STREET 2 NDS Exploit)
<img src="https://cdn.discordapp.com/attachments/368785644173918210/368787222889234432/IMG_20171014_114826.jpg" width="320">
Another successful attempt to exploit FIFA STREET 2 for the Nintendo DS to execute unsigned code from the savegame.

* The exploit supports both US/EUR region carts. 
* EUR version will be supported soon.

Runs in NTR/NDS mode. This exploit works on any of the Nintendo DS family. Including emulators.
###
## Usage for patching the savefile
* Win32: `street2fixsum street2save(US/EUR).sav` 
* Linux: `./street2fixsum street2save(US/EUR).sav`
###
## Triggering the exploit
Navigate to My Street, go to Profile, then go to Edit my Profile

## Credits:
* jerbear64 (Testing the exploit for retail & compiling the street2fixsum.cpp)
* St4rk (Payload code)
* CTurt (For the guide on stack smashing nds games) https://cturt.github.io/DS-exploit-finding.html
