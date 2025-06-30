# MP32C64
MP32C64 is a simple adapter that allows connecting any audio source to the Datassette port of a Commodore VIC-20, 64, 128 or Plus/4 computer.

![Board](https://raw.githubusercontent.com/SukkoPera/MP32C64/master/img/render-top.png)

## Summary
With this adapter, any audio source can be used in place of the proprietary Commodore Datassette, in order to load software into a Commodore computer through the dedicated port.

It was originally developed by the Spanish C64 freak Kopsec, probably inspired by the adapter that came with [1st CD-Edition](https://www.c64-wiki.com/wiki/1st_CD-Edition_(Collection)).

As the name suggests, beside Audio CDs, MP3 files will also work, so a smartphone (provided that you have an old model with an audio jack...) or any other audio player can be used.

PRG files can be converted to audio using the [WAV-PRG](https://wav-prg.sourceforge.io/) software suite.

## Assembly
The original adapter used 6.8k and 68k resistors, but I didn't have those values when I built the first prototype, so I used 4.7k and 47k and they worked well. Probably 10k and 100k would also work, so give these a try before buying new resistors for the purpose.

The adapter can either be built with a PJRAN1X1U01X RCA/Cinch connector or with a SJ1-3525N 3.5" headphone jack connector, according to your preference. Note that the RCA connector will point towards the back, while the headphone jack will point to the right.

## Usage
Usage should be straightforward. The only thing to be careful with is the playback volume: start with 0 and gradually increase it until the Signal LED is constantly on. You can still go up a few ticks from there, experiment a bit until you have successful loads.

## Releases
If you want to get this board produced, you are recommended to get [the latest release](https://github.com/SukkoPera/MP32C64/releases) rather than the current git version, as the latter might be under development and is not guaranteed to be working.

Every release is accompanied by its Bill Of Materials (BOM) file and any relevant notes about it, which you are recommended to read carefully.

## License
The MP32C64 documentation, including the design itself, is copyright &copy; SukkoPera 2025 and is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This documentation is distributed *as is* and WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties OF MERCHANTABILITY, SATISFACTORY QUALITY, FITNESS FOR A PARTICULAR PURPOSE or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

## Support the Project
If you want to get some boards manufactured, you can get them from PCBWay through this link:

[![PCB from PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](xxx)

You get my gratitude and cheap, professionally-made and good quality PCBs, I get some credit that will help with this and [other projects](https://www.pcbway.com/project/member/shareproject/?bmbid=41100). You won't even have to worry about the various PCB options, it's all pre-configured for you!

Also, if you still have to register, [you can use this link](https://www.pcbway.com/setinvite.aspx?inviteid=41100) to get some bonus initial credit (and yield me some more).

You can also buy me a coffee if you want:

<a href='https://ko-fi.com/L3L0U18L' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## Thanks
* Kopsec for designing the original adapter.
* [C64-Wiki](https://www.c64-wiki.com/wiki/Main_Page) for preserving the schematics and various information about the adapter.
* Kinmami for validating the design.
