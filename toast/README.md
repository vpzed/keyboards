# Toast - Simple but Good

<img src="https://raw.githubusercontent.com/vpzed/keyboards/main/toast/media/toast.png" width="200">

A 34 key split ergo keyboard designed with [ergogen](https://github.com/ergogen/ergogen) v3.1

Keyboard had been built from posted gerbers!

<img src="https://raw.githubusercontent.com/vpzed/keyboards/main/toast/media/toast1-pcb-2d.png" width="500">

<img src="https://raw.githubusercontent.com/vpzed/keyboards/main/toast/media/toastv1.jpg" width="1080">

## Ergo Features
- No row stagger
- Aggressive column stagger
- Very aggressive index finger stagger for people with index fingers shorter than ring
- 5 degree splay angle on pinky and ring columns for natural outer finger angle
- No splay on index finger column since the board is for shorter index fingers
- 11 degree angle on middle column from board edge for neutral wrist angle
- Home thumb key centered on inner index row and second thumb key on toward-the-palm motion

## Firmware
- Uses existing QMK a_dux firmware
- Check QMK a_dux Readme for note on setting board "handed-ness" on first flash

## BOM

[Gerbers ZIP file for use with JLCPCB or similar](https://github.com/vpzed/keyboards/raw/main/toast/v1/gerbers/gerbers.zip)

Required:
- 2 Toast PCBs **Note**: The PCBs are reversible, so a minimum order of 5 boards is enough for 2 keyboards and a spare in case of issues
- 34 Kaihl Choc v1 switches (PG1350)
- 34 Choc key caps (17.5mm x 16.5mm like MBK) **Note:** 19.05mm x 19.05mm choc key caps will **not** fit (like WorkLouder's wrk. series)
- 2 TRRS jacks (PJ-320A)
- 2 ProMicro compatible controllers
- 1 USB to USB cable with appropriate connectors for your controllers and computer
- 1 male to male TRRS cable **Note**: TRRS is 4 pole
- 8+ rubber bumpers to use as feet under the PCB for case-less configuration

Optional but Recommended:
- 2 ProMicro sockets **Note**: The socket must be tall enough to allow for the controller connector to fit in both up and down orientations. For example, a MillMax low profile socket does not have sufficient clearance for a Bit-C controller facing down due to the height and placement of the connector, but that socket does have enough clearance for an Elite-C and many micro-USB ProMicro clones.
- 48 socket pins

Optional:
- 2 Reset switches (Tact Switch TVBP06) **Note**: You can also use the pads as a safer way to use the "tweezer method" to reset with no VCC nearby like on the MCU.
