# FPGA
## Device
#### Lattice MachX02 FPGA
- Use LCMXO2-256HC-4SG32C (32-pin QFN, smallest available package)
- https://www.digikey.com/en/products/detail/lattice-semiconductor-corporation/LCMXO2-256HC-4SG32C/3232671?s=N4IgTCBcDaIDIGECyANA8mAtGArANgAkFMAWAZQHEBmMBEAXQF8g
- $4.75
- Symbol - done (new symbol)
- Footprint - done (copied and modified default lib footprint)
- 3D - done (copied )
## Power
#### USB-C Connector
- Use Amphenol 12401948E412A (single row, A/B 5-8)
- https://www.digikey.com/en/products/detail/amphenol-cs-commercial-products/12401948E412A/13683167
- $1.01
- Symbol - done (copied 16 pin symbol)
- Footprint - done (copied default lib footprint)
- 3D - done (grabbed from digikey)
#### eFuse
- Use TI TPS259474LPPWR (10-pin VQFN)
- https://www.digikey.com/en/products/detail/texas-instruments/TPS259474LRPWR/14123976
- $1.27
- Symbol - done (copied from other project)
- Footprint - review (from scratch)
- 3D - done (grabbed from ti)
###### TVS Diode
- Use LittelFuse SMAJ10CA (DO214AC package)
- https://www.digikey.com/en/products/detail/littelfuse-inc/SMAJ10CA/762267
- $0.43
- Symbol - done (copied from default lib)
- Footprint - done (copied from default lib, reviewed with datasheet)
- 3D - done (copied from default lib)
#### 3.3V Converter
- Use TI TPS543320RPYR (14-pin VFQFN)
- https://www.digikey.com/en/products/detail/texas-instruments/TPS543320RPYR/13627248?s=N4IgTCBcDaICoAUDKBWALAZg2ADCAugL5A
- $2.33
- Symbol - Done (copied from other project and reviewed)
- Footprint - Done (copied and modified from UL)
- 3D - Done (copied from UL)
###### Inductor
- Use XEL4030-472MEC
- https://www.coilcraft.com/en-us/products/power/shielded-inductors/molded-inductor/xel/xel4030/xel4030-472/
- $2.10
- Symbol - use default kicad
- Footprint - Done (copied from default lib)
- 3D - Done (copied from default lib)
## Connectivity
#### Headers
- Use 2.54mm pitch headers


# Debug
## USB-JTAG
##### FTDI FT2232H USB-JTAG
- Use FT2232H-56Q (56-pin QFN, smallest available package)
- https://www.digikey.com/en/products/detail/ftdi-future-technology-devices-international-ltd/FT2232H-56Q-TRAY/5994773
- $5.20
- Symbol - Done (created from scratch)
- Footprint - Done (copied from default lib)
- 3D - Done (grabbed from digikey)

##### USBLC6 USB2.0 TVS Array
- Use USBLC6-2SC6 (SOT23 package)
- https://www.digikey.com/en/products/detail/stmicroelectronics/USBLC6-2SC6/1040559
- $0.36
- Symbol - Done (copied from KiCad)
- Footprint - Done (copied from KiCad)
- 3D - Done (copied from KiCad)

## Power
#### eFuse
- Use TI TPS259474LPPWR (10-pin VQFN)
- https://www.digikey.com/en/products/detail/texas-instruments/TPS259474LRPWR/14123976
- $1.27
- Duplicate 
###### TVS Diode
- Use LittelFuse SMAJ10CA (DO214AC package)
- https://www.digikey.com/en/products/detail/littelfuse-inc/SMAJ10CA/762267
- $0.43
- Duplicate
#### 3.3V Converter (integrated inductor)
- Use TI TPSM8282x or TPSM82830x
	- TPSM828214SILR
		- 2.4-5.5V input
		- Fixed 3.3V output (1A)
		- https://www.digikey.com/en/products/detail/texas-instruments/TPSM828214SILR/14124001
		- $2.50
		- Symbol - done (created from scratch)
		- Footprint - done (reviewed digikey UL footprint)
		- 3D - done (grabbed digikey UL footprint)
	- TPSM828301ARDSR
		- 2.25-5.5V input
		- 0.5-4.5V output (1A)
		- https://www.digikey.com/en/products/detail/texas-instruments/TPSM828301ARDSR/22474923
		- $2.50
## Isolation
##### Maxim MAX14131 Digital Isolator
- Use MAX14131FAEE+ (16-pin QSOP, smallest available package)
- https://www.digikey.com/en/products/detail/analog-devices-inc-maxim-integrated/MAX14131FAEE-T/7515946
- $8.49
- Symbol - Done (created from scratch)
- Footprint - Done (created from scratch)
- 3D - Done (grabbed from Digikey UL)
## Connectivity
#### USB-C Connector
- Use Amphenol 12401948E412A (single row, A/B 5-8)
- https://www.digikey.com/en/products/detail/amphenol-cs-commercial-products/12401948E412A/13683167
- $1.01
- Duplicate





