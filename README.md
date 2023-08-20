# Sega Genesis/Mega Drive Model 1 S-Video Mod PCB
Simple PCB that carries the Luma, Chroma, and Ground lines with their respective components for a Model 1 Genesis/Mega Drive equipped with a Sony CXA1145 video encoder, enabling S-Video functionality. It is rare but still possible to instead have a Fujitsu MB3514 video encoder in a Model 1 Genesis/Mega Drive. If that is your case, then use the [Model 2 & 3 S-Video PCB instead](https://github.com/joshman196/Simple-Genesis-Model-2-and-3-S-Video-Private).

**It is recommended to use 28 AWG wire for this install.**

![6VT0fL5](https://github.com/joshman196/Simple-Genesis-Model-1-S-Video-Private/assets/114156648/4d0e9087-ef10-4d96-b74f-245e5ddacec1)

## Parts Needed

- 1x 220µF 6.3V Capacitor
- 1x 75 Ohm Resistor
- 1x 33 Ohm Resistor
- 1x KSC945 Transistor (If you buy this part from somewhere else, double-check that you get the KSC945 and **NOT** the KSC945**C**)

You can buy these components in a kit from [console5.com](https://console5.com/store/cxa1145-simple-s-video-mod-kit.html). Make sure to also pick up an S-Video jack as well, and conveniently enough console5 also offers these in either [socket](https://console5.com/store/mini-din-in-line-socket-4-pin-female-black-pin-type-s-video-s-vhs.html) or [panel mount](https://console5.com/store/s-video-jacks-panel-mount-black-plastic-housing-solder-type.html) configurations. The version you get depends on whether you want to drill the outer shell of your console (flush mount) or not (socket).

## Installation Steps

1. Add the components (capacitor, resistors, transistor) to the PCB and find a suitable place inside your console to put the assembled board at. You may want to put kapton tape on the area of the main board where you plan on setting the PCB at. Make sure your kapton tape layer can cover the entire bottom of the PCB. You may also choose to set it somewhere off of the main board.
2. Connect a wire from pin 15 of the CXA1145 to "C In" on the S-Video PCB.
3. Connect a wire from pin 16 of the CXA1145 to "Y In" on the S-Video PCB.
4. Connect a wire from pin 12 of the CXA1145 to "+5V In" on the S-Video PCB.
5. Connect a wire from pin 1 of the CXA1145 to "GND" on the S-Video PCB.
6. If you have heatshrink tubing that you want to use, you should prepare them on the next set of wires below before soldering the other ends of those wires. **Do not apply the heat to the tubing until after testing your install!**
7. Connect a wire from "C Out" on the S-Video PCB to the Chroma pin on the back of the S-Video jack.
8. Connect a wire from "Y Out" on the S-Video PCB to the Luma/Y pin on the back of the S-Video jack.
9. Connect a wire from "CGND" on the S-Video PCB to the Chroma-Ground pin on the back of the S-Video jack.
10. Connect a wire from "YGND" on the S-Video PCB to the Luma/Y-Ground pin on the back of the S-Video jack.
11. With the wiring all done, stick some more kapton tape from the sides over the PCB to stick it down onto the main board itself, setting the PCB on top of the other layer of kapton tape you put earlier. **DO NOT SET THE PCB DOWN ON THE BARE MAIN BOARD WITHOUT SOME KIND OF INSULATION UNDER THE S-VIDEO PCB TO PREVENT POTENTIAL SHORTS.** Electrical tape may work but that tends to leave a nasty residue, so I wouldn't recommend it.
12. You're done!
