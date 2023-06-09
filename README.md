This project was originally for my own private personal use, but I am deciding to make this a repository anyway.

This is also my first time using vias on a PCB layout! Oh, this was made with KiCAD 7.0, so any earlier release will not work.

The circuit was tested with a 74HC244 IC and TJTAG 3.0.1 and 3.0.2.1 on a few machines with success barring issues with using one 74HC244; replacing it with another 74HC244 from the same set fixed the recognition issue. This is why a 74HCT244 is recommended with this circuit.

--

This same circuit on a perfboard - prototype unit before the final PCB design... photos aren't as clear; my long retired LG G7 ThinQ was better for this.
Also, the jumpers for switching 3V3/5V0 exist because I do not have a DPDT switch on hand.

Top view
![IMG_20230608_184524307~2](https://github.com/AmiSapphire/jtag-wiggler/assets/103345205/48d1f891-af2e-4ab9-b33d-1e8b68564dab)

Bottom view
![IMG_20230608_221627281~2](https://github.com/AmiSapphire/jtag-wiggler/assets/103345205/f6b6edf8-1dbf-433c-84ba-23ddd86b504f)
