# Skywater130-PhysicalVerification
PV Workshop using Skywater 130nm technology - VSD


“Physical Verification using Skywater 130nm technology” Workshop intends to address various issues that come up during the design cycle as DRC/LVS violations. It aims to demonstrate the best approach to mitigate and rectify these violations. The course covers Physical Verification methodology using Magic,Netgen and OpenLane flow. It also explores the SKY130 PDK in detail, the knowledge of which is necessary to generate a robust design. This course starts with giving the basic idea of the design flow, PDK libraries and then takes a deep dive into the intricate concepts of Physical Verification with dedicated lecture and labs for each topic.

 
Day 1 Lectures: Introduction to SkyWater SKY130
	•  Open_pdks
	•  SkyWater PDK
	•  Open tool setups
	•  Libraries
	•  3rd-party packages
	•  Projects
	•  Understanding the Skywater PDK
	•  Layers
	•  Rules
	•  Devices
	•  Libraries
	•  Digital standard cells
	•  I/O cells


Day 1 Labs:
	• Open_pdks installation
	• Installing open_pdks and the SkyWater PDK
	• Project setup best practices
	• Setting up for layout with magic
	• Setting up for schematic capture with xschem
	• Setting up for LVS with netgen
	• Creating a SKY130 device layout in magic
	• Creating a simple schematic in xschem
	• Exporting a schematic to layout
	• Simulating the netlist


Day 2 Lectures: Introduction to DRC and LVS
	• Understanding GDS format
	• Streaming format
	• Layer:Purpose pairs
	• Hierarchy
	• Some tools/scripts for manipulating GDS
	• Understanding extraction and SPICE formats
	• Running extraction
	• ngspice
	• Extraction styles and options
	• ext2spice options
	• Extraction for LVS
	• Parasitic extraction
	• Full R-C extraction
	• GDS reading and writing in magic
	• Readonly option
	• Flatten options
	• Hierarchy & magic's database
	• Polygon subcells
	• Library option
	• Addendum option
	• Noduplicates option
	• Working with GDS styles
	• GDS special purpose styles
	• DRC rules in magic
	• Interactive DRC in magic
	• DRC vs. correct-by-design in magic
	• DRC rules hidden by hierarchy
	• DRC rules in the tech file
	• DRC verification layouts
	• Extraction rules in magic
	• Extraction styles
	• Device types
	• Hierarchical extraction
	• DRC errors uncovered by extraction
	• LVS setup for netgen
	• Setup options
	• Device description
	• SPICE vs. SPICE
	• SPICE vs. verilog
	• Black-boxing
	• Verification by XOR
	• ECO
	• XOR


Day 2 Labs:
	• Basic GDS:
		○ Reading/writing GDS to/from magic
		○ GDS compositing with magic
		○ Vendor GDS
		○ Reading unknown GDS (magic and klayout)
		○ GDS read/write options
	• Basic extraction:
		○ Extracting a SPICE netlist from magic
		○ Extraction options
		○ Parasitic extraction
	• Setup for DRC:
		○ Running magic (on a prepared example)
		○ Using DRC styles
		○ Using alternative tech files
		○ Running sign-off scripts
		○ Viewing DRC in klayout
		○ Setup for LVS
		○ Netgen setup scripts
		○ Running netgen (on a prepared example)
		○ Setup for XOR
		○ Creating an ECO (from a prepared example)
		○ Running XOR

Day 3 Lectures: Front-end and back-end DRC
	• Back-end (metal layer) rules
	• Width
	• Spacing, Notch
	• Wide-spacing
	• Minimum Area
	• Via overlaps
	• Minimum hole
	• Slot rules
	• Via generation rules
	• Local Interconnect
	• Front-end rules
	• Transistor rules
	• Implants, ID layers, Boundary layers
	• Wells, Same-net rules
	• Deep N-well
	• High voltage rules
	• Resistors
	• Capacitors
	• Diodes
	• Fixed-layout devices
	• Miscellaneous rules
	• Off-grid errors
	• Restricted angles
	• Latchup rules
	• Antenna rules
	• Stress rules
	• Density rules
	• Why density rules?
	• Layer density requirements
	• Fill generation algorithm
	• Fill blocking
	• When automation fails
	• Recommended rules
	• Double vias
	• DRC in Magic:DRC styles
	• Dumping and viewing DRC results
	• Fixing DRC errors

Day 3 Labs:
	• Running Magic's interactive DRC
	• Running antenna checks
	• Running Magic's batch DRC
	• Running the fill generation script
	• Running the density checker script
	• Checks with alternative tech files
	• Catching violations by extraction

Day 4 Lectures: Understanding PNR and physical verification
	• OpenLANE/OpenROAD automation 
	• Non – Interactive mode of OpenLANE Flow
	• Interactive mode of OpenLANE Flow
	• Techniques To Avoid Common DRC Errors
	• Techniques To Manually Fix Violations

Day 4 Labs:
	• PNR flow Using OpenLANE Demo

Day 5 Lectures: Running LVS
	• Generating netlists from schematic
	• Generating LVS netlists from layout
	• Differences between LVS netlists and simulation netlists
	• How to prepare netlists for both simulation and LVS
	• Verilog vs. layout
	• Running netgen
	• Pre-match analysis
	• Hierarchical checking and flattening
	• Property checking
	• Pin checking
	• Series/Parallel combining
	• Symmetry breaking
	• Interpreting results
	• Fixing errors

Day 5 Labs:
	• Creating a (simple) hierarchical circuit in schematic
	• Exporting a schematic to netlist
	• Importing a schematic netlist into layout
	• Exporting a circuit layout to netlist
	• Creating a (simple) hierarchical circuit in verilog
	• Running LVS
	• Interpreting LVS results
	• Fixing LVS errors

