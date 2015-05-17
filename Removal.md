# Windows Installer #

  * Open Control Panel
  * Open "Add or Remove Programs"
  * Click on the "XmlSoft - File Monitor" entry and press it's Remove button.
  * Follow the directions within the resulting uninstallation guide.

# Linux Package - GUI #

  * Navigate to System / Administration / Synaptic Package Manager.
  * Enter your root password when prompted.
  * In the quick search bar type "file-monitor".
  * Right click on the File Monitor entry and click on the "Mark for Complete Removal" option.
  * Click the Apply button, click Apply in the resulting dialog and close the following dialogs.
  * Close the Synaptic Package Manager.

# Linux Package - Command Line #

  * Open a shell and type "sudo dpkg -P file-monitor" and click enter.

# OSX (delayed) #

# Source for Windows: #

  * Delete the "C:\Program Files\file-monitor" directory and any links that you may have created which point to any of those files.

# Source for Unix #
  * Download "file-monitor-1.1.0.tar.gz".
  * Uncompress "file-monitor-1.1.0.tar.gz" into the directory "file-monitor".
  * Open a shell and navigate to the "file-monitor" directory.
  * Type "qmake".  This will create the makefile for your system.
  * Type "sudo make uninstall".  This will remove File Monitor and it's associated files from your system.