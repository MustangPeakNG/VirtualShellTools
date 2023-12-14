MustangpeakVirtualShellTools
============================

### Table of contents
1.  [Introduction](#Introduction)
2.  [Package names](#Package-names)
3.  [Installation](#Installation)

## Introduction

The Mustangpeak libraries for Delphi and C++Builder was originally developed by **Jim 
Kueneman** and contains the EasyListView and the VirutalShellExplorer components.
Mustangpeak VirtualShellTools provides Windows Explorer style shell treeview and list
view components for Delphi and C++Builder applications.
The main component TVirtualExplorerTree is a VirtualStringTree decsendant and is
VCL Styles and DPI-aware enabled.

This is a source-only release of VirtualShellTools. It includes designtime and runtime
packages for Delphi and CBuilder and supports Win32 and Win64.

## Package names

VirtualShellTools package names have the following form:

- VirtualShellToolsD.dpk        (Delphi runtime package)
- VirtualShellToolsDD.dpk       (Delphi design time package)

- VirtualShellToolsC.bpl        (C++Builder Runtime for the VCL)
- VirtualShellToolsCD.bpl       (C++Builder Runtime for the VCL)

*RAD STUDIO Athens or later supported.*

## Installation

To install VirtualShellTools into your IDE, take the following steps:

  1. Install first [CommonLib](https://github.com/MustangPeak/CommonLib),
     [EasyListView](https://github.com/MustangPeak/EasyListView) and
     [VirtualTreeView](https://github.com/JAM-Software/Virtual-TreeView) or
     (https://github.com/TurboPack/Virtual-TreeView).
    
     Note that you need to install the Virtual-Treview version from the repo and not
     the GetIt version.

  2. Clone or download and unzip the Github repository into a directory
     (e.g., D:\MustangPeak\VirtualShellTools). 

  3. Start RAD Studio.

  4. Add the source subdirectory (e.g., D:\Mustangpeak\VirtualShellTools\Source) to the
     IDE's library path.

  5. Open and compile the runtime package specific to the IDE being used.   

  6. Open & install the corresponding designtime package.

  7. If you have installed Toolbar2000 or SpTBXLib components and want to use them
     with VirtualShellTools, enable the respective directives in Include\Addins.inc.

Last update on 14 December 2023