---
id: chapter03
title: "Chapter 3: Verifying the ISO"
---

## What's the point?
You should verify your ISO file to make sure that it hasn't been corrupted.  In the event that you have problems booting up your virtual Linux machine from this file, you are assured that a corrupted file is not the culprit.

## What is MD5?
MD5 calculates the value of a file by analyzing it with a cryptographic algorithm and producing an output string.

## Procedure
* In your file browser, go to the directory where files are downloaded.
* Open the sparkylinux-*-lxde-stb.iso.allsums.txt file.  You'll see the expected md5sum value of the SparkyLinux ISO file that you downloaded.
* Open a terminal window, and go to the directory where files are downloaded.
* Check the md5sum value of your SparkyLinux ISO file.  If your host OS is Linux, the terminal command to enter is "md5sum (name of ISO file)".  If your host OS is MacOS, the command is "md5 (name of ISO file)".  If your host OS is Windows, the command to enter is "certUtil -hashfile (name of ISO file) MD5".
* In a moment, you will see the md5sum value of your SparkyLinux ISO file.  It should match the expected value, in which case you are ready to move on to the next chapter.
