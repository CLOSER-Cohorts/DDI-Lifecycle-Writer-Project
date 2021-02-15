# DDI-Lifecycle-Writer
Project to gather issues for extending Cornell DDI-CodeBook Writer

This project will extend / create a new code line based on
https://github.com/ncrncornell/ced2arddigenerator and
https://github.com/ncrncornell/ced2ardata2ddi

It will use the underlying supporting libraries:

https://github.com/ncrncornell/ced2ar-stata-reader and 
https://github.com/ncrncornell/ced2arspssreader

Please use Issues to flag functionality required

A version of the code, that has been given a bit of TLC is at
https://github.com/daxplore/spssreader

The orgiinal code is no longer at: http://opendatafoundation.org/?lvl1=forge 

## Specification

Field level documentation is at https://ddialliance.org/Specification/DDI-Lifecycle/3.3/XMLSchema/FieldLevelDocumentation/ 

Entry point for a datafile is:
FragmentInstance
-> Fragments 
--> Resource Package
---> PhysicalInstanceReference 
---> CategorySchemeReference
---> VariableSchemeReference
