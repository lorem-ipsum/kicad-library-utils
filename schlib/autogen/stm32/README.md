# STM32 library generator
This script turns XML files defining pins for STM32 devices into KiCAD libraries

## Prerequisites
* XML files, taken from STM32CubeMX install (from db/mcu folder)
* XML files for obsolete devices (currently STM32F050xx and STM32F313xx), which
  can be taken from STM32CubeMX install (archives in olddb folder)

## Running
If you have the correct XML files, just run `main.py path/to/xml`, 
where `path/to/xml` is the path to a directory containing all xml files. 
Make sure the XML files have the correct format as there is no error checking.
