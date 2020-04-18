---
id: chapter04
title: "Chapter 4: Creating the Virtual Machine"
---

* In VirtualBox, click on "New" to start the process of creating a new virtual machine.
* You will be asked for the name and operating system.  Use the name "MXLinux", select "Linux" as the type, and select "Debian (64-bit)" as the version.  Then click on "Next".
* You will be prompted for the memory size of your virtual machine.  I recommend allocating about half of the available memory for the virtual machine.  Then click on "Next".
* You will be prompted on whether or not to add a virtual hard disk.  Select the default option ("Create a virtual hard disk now"), and click on "Create".
* You will be prompted for the hard disk file type.  Select the default option, which is to use the VirtualBox Disk Image.  Click on "Next".
* You will be prompted to choose a physical storage option.  Select "Fixed size", and then click on "Next".  While this takes longer initially compared to the default "Dynamically allocated" option, it pays off in the long run with faster performance.
* You will be prompted for the file location and size.  The default size is 8 GB, but if you have plenty of hard drive space, I recommend using more.  I recommend 20 to 100 GB.  Then click on "Create".  (NOTE: If you get a dialog box with an error message that said that the process failed, click "OK" to close the dialog box.  Then click on "Back" to choose a physical storage option.  Select "Dynamically allocated" instead of "Fixed size", click on "Next", enter the desired size of your virtual disk, and then click on "Create".)
* Your new virtual machine will be ready to configure shortly, and you will be back in the main screen of VirtualBox.
