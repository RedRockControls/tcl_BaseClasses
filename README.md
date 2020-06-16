![Pic](https://github.com/RedRockControls/SimpleUnitTestLibrary/blob/master/img/Banner.JPG)

# tcl_BaseClasses

This library is intended for use in Beckhoff TwinCAT3 projects. 

The main components are TExecution and TEventBase

These are described in the following blog posts:

Motivation - [OO Architecture in TwinCAT3](https://www.redrockcontrols.co.uk/?p=588)

TExecution - [OOP in TwinCAT3 – Command Pattern](https://www.redrockcontrols.co.uk/?p=118)

TEventBase - [OOP in TwinCAT3 – Events Framework](https://www.redrockcontrols.co.uk/?p=374)

NOTE:
The library uses the TwinCAT3 EventLogger to display error messages using events defined in the type system of the library. These are exported to a tmc file (BaseClassEventdefinitions.tmc), which must be imported into the type system of the client project. This is done by right-clicking on the "Type System" object in the tree-view of the client project and selecting "Add Existing Item...", then selecting the BaseClass_EventDefinitions tmc file. 

