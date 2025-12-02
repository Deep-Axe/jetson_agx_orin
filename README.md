# Jetson AGX Orin Repository

This repository contains resources for the Jetson AGX Orin modules.

## File Contents

### Jetson AGX Xavier CYPD Controller Firmware

**File:** `Jetson_AGX_Xavier_CYPD4226v12.05.zip`

This archive contains the code and firmware files required to flash the Infineon CYPD controller:

- `.hex` firmware file
- `.cyacd` flash files
- MD5 checksums

### Jetson AGX Orin DevKit Carrier Board Design Files

**File:** `Jetson_AGX_Orin_DevKit_Carrier_Board_Design_Files_A05_20250205.zip`

This archive contains comprehensive hardware design documentation and files for the Carrier Board (A05), including:

- **BOM**: Bill of Materials (`.xlsx`)
- **Gerber Files**: Manufacturing files
- **Schematics**:
  - Concept schematics (`.pdf` and design files)
  - OrCAD schematics (base version `.pdf` and design files)
- **Layout**: Allegro layout files and ASCII extracts
- **PCB**: Assembly drawings and stackup information
- **Database**: ValorODB database


## Currently knowm issues 

- U130 is a VREG SOT23_6D Switch 3V 5.5V AP22615AWU-7 Active High Adjustable OC & Backdrive protection & UL certificate	 Manufacture Part Number AP22615AWU-7 Company	- Diodes Incorporated


- U513 is a IC CONTROLLER USB CYPD4226-40LQXIT QFN40		Manufacturer Part Number- CYPD4226-40LQXIT
Manufacturer - 	Infineon Technologies North America Corp.

- U140 is a VREG LINEAR SOIC8 Low Drop Out 0.2V 3.3V 3.3V 5% % LM9036MX-3.3/NOPB
Manufacturer part number- LM9036MX-3.3/NOPB
Manufacturer -	Texas Instruments, Inc.