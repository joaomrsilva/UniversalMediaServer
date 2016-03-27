
###Universal Media Server 
Universal Media Server is a media server, developed using Java, capable of sharing  videos, audio and images to any DLNA-capable device ( Digital Living Network Alliance)  basically it is a set of interoperability guidelines for sharing digital media among multimedia devices. DLNA works with cable and satellite  to provide link protection on each end of the data transfer.
Universal Media Server is also a DLNA-compliant UPnP media server ( Universal Plug and Play ) is a set of networking protocols that permits networked devices, such as personal computers, printers, Internet gateways, Wi-Fi access points and mobile devices to seamlessly discover each other's presence on the network and establish functional network services for data sharing, communications, and entertainment. UPnP is intended primarily for residential networks without enterprise-class devices.

It allows streaming to many devices including Sony PlayStation 3 (PS3) and PlayStation 4 (PS4), Microsoft Xbox One and 360, many TVs (Samsung, Panasonic, Sony, Vizio, LG, Philips, Sharp), smart phones (iPhone, Android, etc.), Blu-ray players, and more.

Originally it was based on PS3 Media Server which allows the user to access windows media player that's on your computer. If the user is sharing the media player, the ps3 media server will pick up whatever is added to windows media player.Which in time allows the user to have access to any recently added content in the computer using the ps3 system which in turn makes it much easier and faster than burning disks to watch a new movie or listen to the new album the user just downloaded.

Although being based on PS3 Media Server , Universal Media Server , has some enhancements over its predecessor which include web interface support for non-DLNA devices, more supported renderers , automatic bit rate adjustment, and many other transcoding improvements.

###Compatibility
Universal Media Server supports all major operating systems, with versions for Windows, Linux and Mac OS X. The program streams  many different media formats with little or no configuration. It is powered by MEncoder, FFmpeg, tsMuxeR, MediaInfo, VLC, OpenSubtitles.org and more, which combine to offer support for a wide range of media formats , allowing the user to obtain any subtitle and to play any type of video format without having to look for a video player that is able to decode it either it being a .mkv,.mp4,.flv.,.wmv, .avi or .3gp .

###Features
UMS provides many features that might not be available on other popular media servers, such as:  
* **Automatic maximum quality** - 100% video and audio quality maintained when possible by multiplexing.  
* **Intant browsing** - Files can be viewed without the need to wait for folders to be rescanned, which could take a long time with large libraries.  
* **Subtitles** - Even if the device used does not support the subtitle format in the video, it will be added anyway to the video stream. Subtitles can also be added via options on the device.  
* **DTS support** - Full quality DTS instead of downmixing it to a different format.  
* **H.264 transcoding** - Provides the same quality as MPEG-2, with lower filesize, a good option for wireless networks.  
* **True Motion (frame interpolation)** - Adds frames to the regular framerate to make the motion smoother and realistic. This is achieved using InterFrame, an AviSynth plugin that uses SVP libraries.  
* **Overscan compensation** - If the device is a TV, it might cut off the edges of the video, UMS compensates so the whole video is displayed.  
* **Automatic plugin download/install** - It is possible to download and install plugins automatically from within the program.  
* **Unlimited folders on PS3 and Xbox** - Traditionally, PS3 and Xbox 360 only display a limited number of folders, UMS has a work around for that.  
* **AviSynth** - UMS supports AviSynth, a powerful and flexible video and audio serving program.  
* **iTunes** - UMS supports iTunes, the user can browse his iTunes library by playlist, artist, album, genre.  
* **Renderers** - UMS supports rederers with search capability.  
* **Network Bandwith Settings** - User can set the speed of his network to ensure smooth playing.    
* **DVD Support** - DVD playing is supported, whether they are in the DVD drive or in the hard drive.    
* **Archives** - Browsing archives is supported, like ZIP, RAR, GZ, etc.  
* **High-quality video thumbnails** - Maximum quality and resolutions thumbnails that the device can handle.  

UMS is free, that itself can be considered a feature.

###Dependencies

This software requires Java and mediainfo (mediainfo openjdk-7-jre). Optionally, dcraw and VLC can also be used with Universal Media Server.

To compile from source, it requires Eclipse IDE for Java Developers, Maven, m2e Eclipse plugin and EGit Eclipse plugin.

TODO: falar um pouco mais sobre que tecnologias implementa, quais os requesitos funcionais/nao funcionais do projeto
restrições e limitações
