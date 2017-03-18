                     QuikGrid Version 5.3
                     --------------------
Contour or display a grid generated from scattered x,y,z data points

            Copyright (c) 1993-2007 John Coulthard
                      All Rights Reserved

Description
-----------

QuikGrid is a program written for MS WINDOWS which will read in a set of
scattered data points (x, y, z) which represents a surface. The program
will generate a regular grid from this data and then display the surface
as a contour map, or as a grid viewed from an arbitrary viewpoint, with
hidden lines removed. The display may be zoomed and panned using the
left mouse button. Data about features on the display may be selected
using the right mouse button.

QuikGrid runs under MS WINDOWS (95/98/NT/2000/XP etc.) With the
exception of the help facility, it will also run under the WINE MS
Windows Emulator under UNIX (I have tested this using WINE release
0.0.20020411-1 under Debian Linux.)

The display may be printed or output as a DXF data file for input into
Autocad or other programs that support that format. The grid may be
output as a series of XYZ triplets, as a DXF 3DFACE file, as a VRML
(Virtual Reality Meta Language) file or in the ER Mapper raster format.

QuikGrid is easy to use and is very fast. It will run on modest hardware
platforms. It is well suited in situations where it is desired to have a
quick look at a set of data points, for example under field conditions
where only a portable PC is available. On larger computers it is capable
of processing a large number of data points and generating very large
grids (e.g. 3 million data points to a 3000x3000 grid).

QuikGrid is self documented through it's help facility.

Installation
------------

If you are installing from a distributed .zip file unzip the file into
any temporary directory and run QGRID53.EXE.

If you wish to use QuikGrid under WINE:
. I have tested this using WINE release b0.0.20020411-1 under Debian Linux.
. You can use the MS Windows install procedure under WINE.
· Before you read any input data in QuikGrid:
  Under "Edit... Input Options..." uncheck "[ ] Input data in the background"
  and set it as a preference. This does not slow down the loading of data
  but you will no longer get a progress report while loading extremely
  large data bases (typically larger than several hundred thousand data
  points), nor be able to cancel the loading of very large databases while
  they are in the process of loading.
· Do not use "Fast screen update" under the view options.


NOTE: Version 4.6 or later will install by default into the file
C:/Program Files/Quikgrid, NOT C:/quikgrid . If you wish to replace a
version of QuikGrid that is older than Version 4.4 either use the
Browse button to direct the output to your old QuikGrid directory, or
remember to delete the old QuikGrid directory after you install version 4.6.

A version with French menus and dialog boxes will be installed as
quikgridf.exe (The help facility is still English).

QUIKGRID IS FREEWARE
---------------------

QuikGrid is FREEWARE. You can freely use QuikGrid and distribute copies
of the ORIGINAL archive file (typically "qgrid53.zip or qgrid53.exe") as
long as NO ALTERATIONS are made to the archive file and its contents and
no charge is raised except a reasonable fee for distributing costs. Any
other way of distribution of this software is prohibited.

Persons who are unfamiliar with machine grid generation techniques and
contouring may find articles in the June, 1992 issue of Geobyte
interesting. A quote from the conclusion of the article "Contouring: Art
or Science?" by Daniel J. Tearpock, p 43, reads "...contour maps are
interpretations - they are not absolutely correct. " 

                    DISCLAIMER OF LIABILITY 

THIS SOFTWARE IS PROVIDED "AS IS" AND WITHOUT WARRANTIES AS TO
PERFORMANCE OR MERCHANTABILITY. 

THIS PROGRAM IS PROVIDED WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES
WHATSOEVER. BECAUSE OF DIVERSITY OF CONDITIONS AND HARDWARE UNDER WHICH
THIS PROGRAM MAY BE USED, NO WARRANTY OF FITNESS FOR A PARTICULAR
PURPOSE IS OFFERED. THE USER IS ADVISED TO TEST THE PROGRAM THOROUGHLY
BEFORE RELYING ON IT. THE USER MUST ASSUME THE ENTIRE RISK OF USING THE
PROGRAM. 

This is not public domain software. The software is owned by the author
and protected by copyright law.

   John Coulthard
   Perspective Edge Software
   http://www.PerspectiveEdge.com 
