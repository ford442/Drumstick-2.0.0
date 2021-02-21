
# Drumstick Libraries 2.0.0
=========================

Drumstick is a set of MIDI libraries using C++/Qt5 idioms and style. Includes 
a C++ wrapper around the ALSA library sequencer interface: ALSA sequencer 
provides software support for MIDI technology on Linux. A complementary 
library provides classes for processing SMF (Standard MIDI files: .MID/.KAR), 
and Cakewalk (.WRK) file formats. A multiplatform realtime MIDI I/O library 
and a GUI Widgets libraries are also provided for Linux, Windows, and Mac OSX.

Changes for v2.0.0

* New features:
    Code and build systems modernization
    Namespaces reorganization
    New library: drumstick-widgets providing a PianoKeybd widget plugin for Qt Creator and Qt Designer
    New unit tests, for drumstick-widgets and wrk files
    translations for drumstick-widgets and utils
    License GPLv3 for all components
    Each library provides at runtime its version in string format
    Every program reports the linked library names/versions in the about box
    Documentation of the new API for drumstick-widgets
    drumstick-rt: plugins versioning, allowing runtime coexistence between plugins of drumstick-1 and drumstick-2.
* Fixes:
    #2 	drumstick-file: OVE file support removal
    #15 New library drumstick-widgets
    #20 Same names for ALSA Sequencer clients of two hw USB controllers 
    #21 regression: drumstick-guiplayer doesn't remember saved MIDI output device 
    #22 Better rendering of note names in piano keyboard widget
    drumstick-vpiano: fixed SonivoxEAS saved connection string 
    
Compilation minimum requirements for all platforms: CMake 3.9 and Qt 5.7

Copyright (C) 2009-2020, Pedro Lopez-Cabanillas
License: GPL v3 or later

Project web site
https://sourceforge.net/p/drumstick

Online documentation
https://drumstick.sourceforge.io/docs/

Downloads
https://sourceforge.net/p/drumstick/files/2.0.0/
