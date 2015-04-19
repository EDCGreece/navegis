# Introduction #

**NAVeGIS** is a _Navigation_ application for use with custom or open data maps, such as the ones provided from _OpenStreetMap_, at http://www.openstreetmap.org/ or from the data provided from the services at http://garmin.openstreetmap.nl.

# Details #

  * **NAVeGIS** can retrieve data from custom and unlocked, non _NT_ map files, or from unlocked and uncompressed _NT_ map files, in the _IMG_ file format.
  * The application can connect with device’s internal _GPS_ module either utilizing the _GPS intermediate driver_, or connecting with any internal or external _GPS_ unit, via the device’s serial interface.
  * Note that the _GPS intermediate driver_ can only be used when the library is available by the operating system and therefore some older _PocketPC_ or _WinCE_ devices might not present this possibility.
  * The serial interface management utilizes the open source _OpenNETCF Serial Library_, which is available at http://serial.codeplex.com, under the _MIT (Copyright (c) 2003-2009 OpenNETCF Consulting, LLC)_, license.
  * The **NAVeGIS** software is provided under the _GNU General Public Licence, Version 3_.