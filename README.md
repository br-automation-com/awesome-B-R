# awesome-B-R [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome [B&amp;R](https://www.br-automation.com)  frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff.To add, remove or change things on the list: please submit a [pull request](https://github.com/hilch/awesome-B-R/pulls).

---

## Infrastructure
*alarm handling, recipe handling, data logging, user handling etc.*

### based on mapp Services
* [mappDatabase](https://github.com/br-automation-com/mappDatabase-Demo) - Sample project for a basic recipe system using mappDatabase and mappView
* [mappData](https://github.com/br-automation-com/mappView-Recorder) - This is a sample project for a data recorder with mappView and mappData
* [mappBackup](https://github.com/br-automation-com/mappView-Backup) - Sample for a software management with mappView and mappBackup
* [mappRecipe](https://github.com/br-automation-com/mappView-Recipe) - Sample for a user management with mappView and mappRecipe

### based on standard libraries
* [simple recipe handling](https://github.com/hilch/dataobj-recipe) - Automation Studio demo: simple recipe handling with data objects (Library DataObj)
* [FindUsbStickOnBAndRPlc](https://github.com/hilch/FindUsbStickOnBAndRPlc) -Search USB Stick connected to a B&amp;R PLC and use it as file device for FileIO - Library.
* [simple data trace](https://github.com/hilch/PLC-data-trace) - simple data trace (Automation Studio) records PLC variables in a high priority task and save the data to CSV file afterward.
* [Connect USB sticks](https://github.com/br-automation-com/AS-USB) - This is a sample project for automatically mounting multiple USB sticks on a B&R PLC.
* [Connect a network share](https://github.com/br-automation-com/AS-NET) - This is a sample project for mounting a network share on a B&R PLC.
* [BrbLib](https://github.com/br-automation-com/BrbLibs-lib-src]) - Many useful functions/function blocks to solve general requirements at programming a B&R plc

### Security
* [BrSecurity](https://hilch.github.io/BrSecurity) - Automation Studio Lib with Security functions (Password/Encrypt/Decrypt)

### Mathematics
* [RandomLib](https://github.com/brownNinja17/RandomLib) - RandomLib is an Automation Studio library to generate random data.

### Community libraries
* [brOscatLib](https://github.com/tkucic/brOscatLib) - B&R Automation studio port of the popular Oscat libraries


---

## Visualisation 

### based on mapp View
* [Mapp View Getting Started](https://github.com/hilch/mapp-view-getting-started) - Getting Started with B&R mappView
* [mapp View wiki](https://github.com/stephan1827/mappView/wiki) - Collection of B&R mappView tips and code snippets
* [mapp View User Management](https://github.com/br-automation-com/mappView-User) - Sample for a user management with mappView
* [mapp View File Explorer](https://github.com/br-automation-com/mappView-File-Explorer) - Sample for a file explorer with mappView
* [mapp View Recipe Management](https://github.com/br-automation-com/mappView-Recipe) - Sample for a user management with mappView and mappRecipe
* [mapp View Data Recorder](https://github.com/br-automation-com/mappView-Recorder) - This is a sample project for a data recorder with mappView and mappData
* [mapp View Logbook](https://github.com/br-automation-com/mappView-Logbook) - Read the PLC logbook with mappView
* [mapp View Software Management](https://github.com/br-automation-com/mappView-Backup) - Sample for a software management with mappView and mappBackup

### based on VC4
* [BrbLibVc4](https://github.com/br-automation-com/BrbLibs-lib-src) - Many useful functions/function blocks for a transparent and intuitive coding of a Visual Components 4 logic.

### based on HTML
* [webdemo](https://github.com/hilch/br-plc-as-webserver) - demo: use B&R plc as webserver

---

## Vision
* [Vision Demo App](https://github.com/br-automation-com/mappVision-Demo) - Demo application for B&R vision camera
* [Vision Scipt](https://github.com/TomasVostrel/mapp_vision_files) - Python app that generates B&R mapp Vision configuration files

---

## Motion
*single axis, cnc, robotic etc*

### Documentation
* [acopos-cheat-sheet](https://github.com/hilch/bar-acopos-cheat-sheet) - ACOPOS Cheat Sheet
* [ACOPOStrak inkscape](https://github.com/hilch/ACOPOStrak-Inkscape-Template) - Use Open Source Tool 'Inkscape' to draw ACOPOS-Trak-Systems developed by B&amp;R

### based on mapp Motion
* [Mapp Motion Getting Started](https://github.com/hilch/mapp-motion-getting-started) - This tutorial shows how to use B&amp;R "Mapp Motion" Technology Package to implement a single axis project on an ETA training system
* [demo-MpCnc-with-mapp-motion](https://github.com/hilch/demo-MpCnc-with-mapp-motion) - Automation Studio demo cnc application with mapp components (MpCNC based on mapp motion)
* [mapp-robotics-getting-started](https://github.com/hilch/mapp-robotics-getting-started) - This tutorial shows how to use B&amp;R "Mapp Motion" Technology Package to implement a Delta Robot (Mapp Robotics)
* [mapp-motion-positioning-acoposinverter](https://github.com/hilch/mapp-motion-positioning-acoposinverter) - position a sensorless induction motor with mapp Motion


### based on ACP10/ARNC0
* [demo-MpCnc-with-ACP10-ARNC0](https://github.com/hilch/demo-MpCnc-with-ACP10-ARNC0) - demo cnc application (Automation Studio) with B&R mapp components (MpCNC based on ACP10/ARNC0) 

### based on standard libraries
* [acinvlib](https://github.com/hilch/ac_invlib) - B&amp;R Automation Studio Library for ACOPOSinverter
* [Motorky](https://gitlab.com/br_support/Motorky) - This library can perform simple positioning tasks with a stepper motor, frequency inverter or DC motor

---

## Process control

### based on mapp Control
* [MpTemp demo1](https://github.com/hilch/demo-MpTemp) - Automation Studio demo application with mapp component MpTemp

### based on standard libraries
* [ap3131](https://github.com/hilch/demo-AP3131) - B&R Automation Studio demo: how to get data from X20 energy metering module X20AP3131
* [demo-AsIOVib](https://github.com/hilch/demo-AsIOVib) - shows how to upload raw data from X20CM4810 condition monitoring module. Uses 'AsIOVib' / 'vbioCtrlCM4810Ex1'


## Tools
*Useful tools for B&amp;R PLCs*

* [SystemDumpViewer](https://github.com/bee-eater/SystemDumpViewer) - Viewer for SystemDump.xml files of B&amp;R PLCs with a few nice features.
* [brwatch](http://hilch.github.io/brwatch/) - small and portable service tool for B&amp;R PLCs. list, watch and change process variables, start and stop task, search and reboot CPUs, change IP-settings. Additionaly it logs PV values to CSV- Files
* [brsnmp](https://github.com/hilch/brsnmp) - perform PVI-SNMP commands for B&R plcs (list/search PLCs, change IP settings etc.)
* [ListAllBurPLCs](https://github.com/supportcz/ListAllBurPLCs) - This tool lists all B&R PLCs on network
* [simple data trace](https://github.com/hilch/PLC-data-trace) - simple data trace (Automation Studio) records PLC variables in a high priority task and save the data to CSV file afterward.
* [openSAFETYLogbrowser](https://github.com/banickn/openSAFETY-logbrowser) - a log browser application for openSAFETY used with a openPOWERLINKMN based on Electron.
* [acopos-cheat-sheet](https://github.com/hilch/bar-acopos-cheat-sheet) - ACOPOS Cheat Sheet
* [StructuredText Language Package for ATOM](https://github.com/tmatijevich/language-as-structured-text) - ATOM support for IEC 61131-3 Structured Text and Automation Studio (AS) projects including syntax highlighting, snippets, and auto-completion.
* [StructuredText Language Package for VS Code](https://github.com/Serhioromano/vscode-st) - Visual Studio Code support for IEC 61131-3 Structured Text 
* [automation-studio-editor-dark](https://github.com/boaz001/automation-studio-editor-dark) - Dark mode for Automation Studio
* [Automation-Studio-One-Dark](https://github.com/staber/Automation-Studio-One-Dark) - One Dark inspired theme for B&R Automation Studio
* [systemdump.py](https://github.com/hilch/systemdump.py) - create and load a system dump for B&R PLC from the command line
---

## Communication

* [Modbus TCP master (.NET)](https://github.com/stephan1827/modbusTCP) - Visual Studio .NET modbusTCP class implementing a Modbus TCP master driver
* [Modbus TCP master (.NET) for X20BC0087](https://github.com/stephan1827/modbusTCPBR-DotNET) - Visual Studio .NET modbusTCP class implementing a Modbus TCP master driver for the B&R X20BC0087 bus controller
* [modbusTCP Automation-Studio Library](https://github.com/stephan1827/modbusTCP-Automation-Studio) - modbusTCP library for Automation Studio with legacy runtimes that don't support native modbusTCP
* [AsUdp AsTcp demo1](https://github.com/hilch/demo-AsTcp-AsUdp) - Automation Studio demo: how to use the TcpIp- system- libraries "AsTcp" and "AsUdp" 
* [openPOWERLINK](http://openpowerlink.sourceforge.net/web/) - openPOWERLINK - An Open Source POWERLINK protocol stack
* [openPowerlinkQtApp](https://github.com/OpenAutomationTechnologies/openPOWERLINK_Qt_App) Advanced QT app for openPOWERLINK v2.x
* [DatabaseCreatorForAsix](https://github.com/tomaszkudla/DatabaseCreatorForAsix) - Application that helps developing automation systems with B&R X20 PLCs and Asix Evo 9.
* [B&R RFID reader sample for .NET](https://github.com/stephan1827/RFID-DotNET) - Sample project for accessing B&R RFID reader with Visual Studio
* [OpcUaSamples](https://github.com/br-automation-com/OpcUaSamples-sample-AS) - Samples for configuration and coding OpcUa in Ansi-C and StructuredText since AS4.1 to the newest AS version with many explainings and hints

---

## HTML, CSS, Javascript

* [web-memoryleak](https://github.com/hilch/web-memoryleak) - let javascript allocate more and more memory to test embedded web panels (eg. B&amp;R T50, T30 panels)

## IOT

* [br-sitemanager-azure-demo](https://github.com/hzeitlhofer/br-sitemanager-azure-demo) - B&amp;R SiteManager Demo for Azure IoT
* [paho.mqtt.c-ar](https://github.com/br-automation-com/paho.mqtt.c-ar) - MQTT Client Library for Automation Runtime based on eclipse/paho.mqtt.c
* [azure-iothub-instructions](https://dv-br-automation.github.io/azure-iothub-instructions/) - Getting started guide for Azure IoT Hub on B&R APCs


