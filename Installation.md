# Windows #

  * Download "file-monitor-1.1.0-installer.exe".
  * Double click the file-monitor-1.1.0-installer.exe file and follow the installation guide.

# Linux Package - GUI (Ubuntu 9.04 and above - Qt 4.5 or greater required) #

  * Download the .deb package for your architecture.  For example: file-monitor\_1.1.0-1\_amd64.deb is the .deb for x86-64 machines.
  * Double click on the .deb package and the "Package Installer" dialog will appear.
  * Click the "Install Package" button.
  * Enter your root password when prompted.
  * Close the "Installation finished" and "Package Installer" dialogs.
Note: If you experience any problems installing the debian package, you will need to install from source.

# Linux Package - Command Line (Ubuntu 9.04 and above - Qt 4.5 or greater required) #

  * Download the .deb package for your architecture. For example file-monitor\_1.1.0-1\_amd64.deb is the .deb for amd64 machines.
  * Open a shell and navigate to the directory containing the .deb file.
  * Type sudo dpkg -i followed by the name of the .deb. For example: sudo dpkg -i file-monitor\_1.0.1-1\_amd64.deb
Note: If you experience any problems installing the debian package, you will need to install from source.

# OSX (delayed) #

# From Source (Windows) #
  * Download and install the Qt framework (4.5 or higher) for Windows from: http://qt.nokia.com/downloads
  * Ensure that the Qt bin directory (Qt/20xx/qt/bin) and the Qt Mingw bin directory (Qt/20xx/mingw/bin) is in your PATH environment variable.
  * Download "file-monitor-1.1.0.tar.gz".
  * Uncompress "file-monitor-1.1.0.tar.gz" into the directory "file-monitor".
  * Open a command prompt and navigate to this directory.
  * Type "qmake".  This will create the makefile for your system.
  * Type "mingw32-make release install".  This will compile and install File Monitor to "C:/Program Files/file-monitor".
  * Make a link from the executable "file-monitor.exe" in the installation directory to your desktop.

# From Source (Unix) #
  * If qt4-dev-tools version 4.5 or greater is available for your platform, install it. Otherwise, follow the next two steps and download it from Nokia themselves.
  * Download and install the Qt framework (4.5 or higher) for your OS from: http://qt.nokia.com/downloads
  * Ensure that the Qt bin directory (Qt/20xx/qt/bin) is in your PATH environment variable.
  * Install a compilation toolchain (build-essential on linux).
  * Download "file-monitor-1.1.0.tar.gz".
  * Uncompress "file-monitor-1.1.0.tar.gz" into the directory "file-monitor".
  * Open a shell and navigate to the "file-monitor" directory.
  * Type "qmake".  This will create the makefile for your system.
  * Type "sudo make install".  This will build and install File Monitor on your system.