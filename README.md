# kicad-symbols
Some KiCad symbols for IC's that I use that are not in KiCad that I created the symbols for (and using the standard footprints in KiCad).
Use at own your own RISK (see LICENSE for specifics).

## Usage
The components are split up in libraries mainly by function.
If you want to use a single part only make sure you download all the \<library name>.* files and not just the \<library name>.lib if there are more files with the same name but different extension.
Other than that follow the default course for including the symbols in KiCad (Preferences -> Manage Symbol library in KiCad 5.1.10 at least).


# Included symbols

## LDO_Holtek.lib
Some symbols to define some of the LDO's that Holtek produces (https://www.holtek.com/)

- HT73xx
- HT73xx-1
- HT73xx-2
- HT73xx-3
- HT-78xx

## Battery_ics.lib
Some symbol relating to battery management/chargers (battery protection, chargers etc.).

- TP4056    (http://tp-asic.com/ or http://www.tp4056.com)
- DW01xx (https://www.ic-fortune.com/eng)

## mosfet-n-channel.lib
A library containing N-Channel MOSFETs.

- FS8205    (https://www.ic-fortune.com/eng)
- FS8205A   (https://www.ic-fortune.com/eng)
- IRLML2502 (Internal Rectifier, now Infineon https://www.infineon.com/)

## VoltageSupervisors.lib
A library containing some extra voltage detectors.

- KA75xxx (Fairchild)