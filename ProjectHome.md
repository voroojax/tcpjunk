Tcpjunk is a general TCP protocols testing and hacking utility.

### Main features: ###

  * Supports IPv4/IPv6
  * Automatically send/receive data according to predefined session setup
  * Client/Server mode
  * Supports SSL
  * Dynamic data insertion and manipulation using tags
  * Traffic generation
  * GUI mode

### News: ###

**2.9.03**
  * Added Tamper tag.
  * Added max segment option.
  * Many updates to GUI.
  * Bug fixes.

**2.8.21**
  * Fixed issue with initial session timeout
  * Added long options.
  * Help and man page updated.

**2.8.11**
  * 2.8 is out of beta
  * Many more GUI updates and fixes
  * Many other bug fixes

### Screenshot (in GUI mode): ###

![http://tcpjunk.googlecode.com/files/tcpjunk.png](http://tcpjunk.googlecode.com/files/tcpjunk.png)

### Requirements: ###

  * Updated GNU/Linux based system
  * GTK+ 2 Toolkit
  * OpenSSL Toolkit
  * GtkSourceView 2
  * pkgconfig utility

### History: ###

**2.8.05 BETA**
  * Many GUI improvements
  * Removed UDP support (for now)
  * Bug fixes

**2.8.01 BETA**
  * Added IPv6 support
  * Added UDP Client support (UDP Server support in progress)
  * Added character array tag
  * Added option for reusing random source IP's for multiple sessions (-N)
  * Manual page updated
  * Many bug fixes

**2.7.01**
  * Added daemon mode (-a)
  * Fixed sequential files (-e) flaw in server mode
  * Fixed version number

**2.6.92**
  * Fixed crash when using -f/-e options with binary files
  * Fixed memory leaks when using multiple sections
  * Minor GUI changes

**2.6.90**
  * Redesigned encode tag

**2.6.87**
  * Added -e option, sequential files from current directory
  * bug fixes

**2.6.86**
  * Fixed crash in CLI (in some distributions).
  * Added encode tag.

**2.6.80**
  * Added multiple session tabs
  * Undo functionality
  * IP options -P and -R fixed (broken since 2.660)
  * Added "last data" option to fuzz and count tags
  * Many other fixes

**2.672**
  * Fixed crash related to tags in binary session data
  * Fixed count tag in server mode
  * Added verbosity to random file option
  * Fixed tag parsing order issue
  * Other minor fixes

**2.670 BETA**
  * Update: 2.670 still has some issues, flagged as beta (latest stable ver is 2.649).
  * Bulletproofed tag system
  * Added new 'counter' tag
  * Added hexdump feature
  * Misc bug fixes.

**2.661 BETA**

  * Fixed bug in 'system' tag insertion
  * Minor layout and highlight improvements

**2.660 BETA**

  * Added manual page
  * Added syntax highlighting
  * Removed session file size limit
  * Added source port option
  * Improved tags functionality
  * Many bug fixes

**2.649**

  * Fixed crash in GUI/Verbose mode

**2.648**

  * Added option to use random session files from current directory (-f)
  * Added verbosity to CLI (-v) / GUI mode