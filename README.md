# DVBViewer PVR
DVBViewer PVR client addon for [MrMC] (http://mrmc.tv)

supporting streaming of Live TV & Recordings, EPG, Timers.

## Build instructions

### Linux

1. `git clone https://github.com/mrmc/mrmc.git`
2. `git clone https://github.com/mrmc/pvr.dvbviewer.git`
3. `cd pvr.dvbviewer && mkdir build && cd build`
4. `cmake -DADDONS_TO_BUILD=pvr.dvbviewer -DADDON_SRC_PREFIX=../.. -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=../../xbmc/addons -DPACKAGE_ZIP=1 ../../xbmc/project/cmake/addons`
5. `make`

##### Useful links

* [DVBViewer PVR setup guide] (http://kodi.wiki/view/Add-on:DVBViewer_Client)
* [DVBViewer PVR user support] (http://forum.kodi.tv/forumdisplay.php?fid=219)
* [MrMC's PVR user support] (http://forum.mrmc.tv)
* [MrMC's PVR development support] (http://forum.mrmc.tv)
