This project is a demonstration of the Pmod VGA with the Cora Z7-07S. With the Pmod VGA plugged into Pmod connectors JA and JB, a 1080p test screen is generated on the connected VGA monitor. This screen consists of gradient color bars and a point bouncing around in a box in the lower left hand corner of the screen.

In order to use this demo, a [Pmod VGA](reference.digilentinc.com/reference/pmod/pmod-vga/start), a [Cora Z7-07S](reference.digilentinc.com/reference/programmable-logic/cora-z7/start), a VGA Monitor, and a VGA cable are required. For the Cora Z7-10 version of this project, see [this repo](https://github.com/Digilent/Cora-Z7-10-Pmod-VGA).

WARNING!!! This project is only supported in the 2017.4 version of Vivado.

In order to program the project onto an FPGA:

1. 	Download the most recent release ZIP archive (not the source ZIP) from the repo's [releases page](https://github.com/Digilent/Cora-Z7-07S-Pmod-VGA/releases).

2. 	Extract and open the downloaded ZIP. Double click on "Cora-Z7-07S-Pmod-VGA.xpr". This will launch an archived version of the project, in which a bitstream has already been generated.

3. 	Open the Vivado Hardware Manager, select "Open Target", and find the target board.

4.  Program top.bit, found in the Cora-Z7-07S-Pmod-VGA.runs/impl_1/ subdirectory of the extracted archive, onto the target.

For more information on how this project is version controlled, see the [digilent-vivado-scripts repo](https://github.com/artvvb/digilent-vivado-scripts), which contains several Python and TCL scripts for maintaining a Vivado project on Github.
