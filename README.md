# docker-qgis-base



A base repo upon which docker-egis-desktop and docker-egis-server are built.


You might be wondering why these dependencies are not just part of the 
QGIS-Desktop image. This was motivated by the fact that docker times out
during the build of QGIS so I wanted to separate the concerns from
* base OS
* base OS with dependency libs installed
* QGIS installation
* QGIS Server installation

For QGIS Versions 2.x use the v2 recipe folder.
For QGIS Versions 3.x use the v3 recipe folder.



Tim Sutton
May 2016
