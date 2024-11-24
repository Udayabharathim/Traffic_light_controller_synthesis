# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

# Synthesis RTL Schematic :
![WhatsApp Image 2024-11-24 at 4 36 36 PM](https://github.com/user-attachments/assets/a7d6198a-94f8-4543-b26f-2b0d74c33348)

## Area report:
![WhatsApp Image 2024-11-24 at 4 36 43 PM](https://github.com/user-attachments/assets/3e7850d2-3676-4db8-b60f-a226894c7376)


## Power Report:
![WhatsApp Image 2024-11-24 at 4 36 51 PM](https://github.com/user-attachments/assets/55cf40ce-ab53-4039-8b2b-f5f329709f9d)


## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
