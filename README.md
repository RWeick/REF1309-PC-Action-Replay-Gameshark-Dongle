# REF1309-PC-Action-Replay-Gameshark-Dongle
The kicad schematic, PCB file, and PIC Microcontroller dump of the PC Action Replay / Gameshark Dongle for use with Win95/98

Everything necessary to produce the security dongle for the Win 95/98 PC Gameshark and Action Replay software. Details on the functionality of the PIC12C508A can be found [here.](https://github.com/parasyte/picard) Though that page discusses the PS1 Gameshark Pro 12C508A, the code used on both PICs is nearly identical. There are small differences not tied to operation. This wouldn't have been possible without [Nes-player4Life](https://github.com/Nes-player4Life) who bravely subjected his PC Gameshark Dongle to science in order for this to exist, and [Parasyte](https://github.com/parasyte) who meticulously reverse engineered the function of the PIC12C508A available at the above link.

The parallel port connectors are arranged as such: from the orientation of the image shown, the male connector is on the left, and the female is on the right. 

This dongle is identical to the [PC Gameshark Dongle](https://github.com/RWeick/PC-Gameshark-Dongle) I had previously reverse engineered here, with the exception that Datel had updated the PCB layout. All of the components, values, and code is otherwise the same.

PCB Thickness: 1.2 mm

![image](https://github.com/RWeick/REF1309-PC-Action-Replay-Gameshark-Dongle/blob/main/REF1309.png)
