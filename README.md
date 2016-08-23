Modified version of XBMCnfoTVImporter that works with Emby nfo files.

XBMCnfoTVImporter.bundle-for-Plex
=================================
The agent is part of the Unsupported Appstore plugin. Installing it, will make
installation and updates of the agent very easy. You can find the appstore here:
https://forums.plex.tv/index.php/topic/151068-unsupported-app-store-as-in-totally-unsupported-is-currently-offline/

Alternatively you can install manually by downloading the [zipped bundle](https://github.com/gboudreau/XBMCnfoTVImporter.bundle/archive/master.zip) from github, extract it, rename it to  **XBMCnfoTVImporter.bundle** and copy it into the plex Plug-ins directory.

User MattJ from the plex forum reported the following steps to install on ubuntu 14.04:
- Download from github and unzip
- Remove "-master" from the end of both folder names.
- Copy them to the folder:  /var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins
- Find the group number for user "plex" by command "id plex".
- "cd" to folder in step 3 and change ownership of both XBMC bundles: "sudo chown plex:{gid} XBMC*"
- run "sudo service plexmediaserver restart".
Done.
