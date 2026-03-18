# Active probe project

Read about this project at https://jmw.name/projects/active-probe/

## Repository structure

* `board`: schematic and layout design files
	- `Mfg`: Gerbers and manufacturing outputs
* `measurement`: prototype performance measurements
* `simulation\openems`: openEMS simulation files
	- `probe`: input network simulation
	- `transmission-lines`: coplanar waveguide transmission line simulation
* `simulation\spice`: circuit simulations

## APS2010

APS2010 is a probe version manufactured and sold by **[rogprobe.com](https://rogprobe.com/)**, based on the original open hardware design released under the **CERN-OHL-S-2.0** license.

This work is distributed under the same licensing terms as the original design.

All CAD data is available in this repository.

### Main modifications
- Added **5 V DC power input**, allowing the probe to be powered directly from the oscilloscope  
- Slight adjustments to the **PCB probe tip geometry**

### License

This project is based on an open hardware design released under the **CERN-OHL-S-2.0** license.  
All modifications and redistributed design files remain under the same license.
