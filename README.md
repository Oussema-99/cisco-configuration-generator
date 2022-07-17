# cisco-configuration-generator

Project by: Oussama Ghorbel

This project is designed to help Network Engineers generate VxLAN-EVPN Configuration for Nexus devices using an Excel File.

Generated configuration files will be stored in "output/{date-time}".

To explains how this Script works, there is an Example in "example/" which contains:
	1) Topology File
	2) Excel File with all the variables configured
	3) 1 Configuration File for every device in the topology
	
Note: For the script to work correctly make sure that:
	1) The excel file is configured correctly and is stored under "excel_files/"
	2) "output/" directly is created in the root of the project
	3) Do NOT edit the jinja2 files unless you know what you're doing

Have fun!
	
	
