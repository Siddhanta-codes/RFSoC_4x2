This repository contains a Vivado block design exported as a TCL script (Project_3.tcl).
You can recreate the design on your local Vivado installation by following the steps below.

Requirements

- Vivado 2024.1 or newer

Compatible board files (e. Zynq UltraScale+ RFSoC 4x2 or xzcu48dr)

- Windows or Linux OS

How to Open the Design

- Launch Vivado
- Open Vivado on your PC.

- Open the Tcl Console
- In the Tcl Console at the bottom of the Vivado window, navigate to the folder where you saved this repository

  cd <path_to_folder>
  Example:
  cd C:/Users/YourName/Documents/Project_3

- Run the Tcl Script
- source Project_3.tcl
  This will automatically recreate the Vivado project and open the block design.

- Open the Block Diagram
  Go to:
  Flow Navigator → IP Integrator → Open Block Design
  and open the design (e.g., adc2gsps_bd.bd).

- Notes
  If Vivado shows a warning about a remote BD path, make sure no project with the same name is already open.

  You can rename the design inside the .tcl file or set:

  set run_remote_bd_flow 0
  before sourcing if needed.

