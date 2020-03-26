Luminode 2 design notes

File descriptions:
------------------
mainBoardBare.stl - 3D representation of blank main PCB, all versions use these same dimensions
    Overall dimmensions (in mm) 66 x 33 x 1.6
    Corner notches 4.7 x 4.7

mainBoardDimmer.stl - 3D representation of PCB for dimmer version with major components populated

radioBoard.stl - 3D representation of blank radio board PCB
    Overall dimmensions 55.6 x 22.6 x 0.8

Key components:
---------------
MOSFETS (x 2):
    https://www.digikey.com/product-detail/en/on-semiconductor/FDP33N25/FDP33N25-ND/1154602
    or
    https://www.digikey.com/products/en?keywords=FDP8N50NZ

Radio MCU:
    https://www.digikey.com/product-detail/en/espressif-systems/ESP32-PICO-D4/1904-1029-1-ND/9381738

Relay: 
    https://www.digikey.com/product-detail/en/omron-electronics-inc-emc-div/G5LE-14-DC3/Z3326-ND/1815628

Fuse:
    https://www.digikey.com/products/en?keywords=0216010.MXESPP

Power Supply:
    https://www.mouser.com/ProductDetail/MEAN-WELL/IRM-02-33?qs=sGAEpiMZZMuWiaalG5TUgO6fhgi59iJofxxuZXFRmkhzCWy1sCHy5g%3D%3D

Tactile buttons (x 2):
    https://www.digikey.com/product-detail/en/c-k/PTS526-SMG15-SMTR2-LFS/CKN12222-2-ND/10056627

RGB LEDs (x 2):
    https://www.digikey.com/product-detail/en/inolux/IN-S126TASRGB/1830-1052-1-ND/7604685

Possible Boost converter parts for battery version:
https://www.digikey.com/product-detail/en/torex-semiconductor-ltd/XCL210C331GR-G/893-1255-1-ND/5964797
https://www.digikey.com/product-detail/en/microchip-technology/MCP1640T-I-CHY/MCP1640T-I-CHYCT-ND/2258621

Also for battery version moving to off the shelf battery holder:
    https://www.digikey.com/product-detail/en/BC2AAAPC/BC2AAAPC-ND/2439242


Additional components yet to be selected:
-----------------------------------------

thermistor to detect overheating
zebra connector


General notes:
--------------
