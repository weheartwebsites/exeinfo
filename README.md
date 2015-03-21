(https://img.shields.io/badge/license-MIT-blue.svg)

# exeinfo (cli)

Original author: http://www.nirsoft.net/utils/exeinfo.html

## Requirements

* Visual C++ Redistributable Packages for Visual Studio 2013 (free: http://www.microsoft.com/en-us/download/details.aspx?id=40784)
* Windows XP - Windows 8.1 (32bit or 64bit)

## Usage

```
exeinfo.exe other.exe
```

## Project Overview

### exeinfo.vcxproj
This is the main project file for VC++ projects generated using an Application Wizard. It contains information about the version of Visual C++ that generated the file, and information about the platforms, configurations, and project features selected with the Application Wizard.

### exeinfo.vcxproj.filters
This is the filters file for VC++ projects generated using an Application Wizard. It contains information about the association between the files in your project and the filters. This association is used in the IDE to show grouping of files with similar extensions under a specific node (for e.g. ".cpp" files are associated with the "Source Files" filter). 

### exeinfo.cpp
This is the main application source file.

### exeinfo.h
This is the main application header file.

## Other files

### StdAfx.h, StdAfx.cpp

These files are used to build a precompiled header (PCH) file named exeinfo.pch and a precompiled types file named StdAfx.obj.

