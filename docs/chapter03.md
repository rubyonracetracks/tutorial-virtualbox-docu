---
id: chapter03
title: "Chapter 3: Verifying the ISO"
---

## What's the point?
You should verify your ISO file to make sure that it hasn't been corrupted.  In the event that you have problems booting up your virtual Linux machine from this file, you are assured that a corrupted file is not the culprit.

## What is SHA256?
SHA256 is a kind of cryptographic hash function, which calculates the value of a file by analyzing it with a cryptographic algorithm and producing an output string.

## Why use SHA256 instead of MD5SUM?
MD5SUM is considered to be a less secure cryptographic hash function than SHA256.

## Procedure
* Open a terminal window, and go to the directory where you downloaded your 64-bit MX Linux ISO file.
* Check the SHA256 value of your 64-bit MX Linux ISO file.  If your host OS is Linux, the terminal command to enter is "sha256sum (name of ISO file)".  If your host OS is MacOS, the command is "sha256 (name of ISO file)".  If your host OS is Windows, the command to enter is "certUtil -hashfile (name of ISO file) SHA256".
* In a moment, you will see the SHA256 value of your MX Linux ISO file.  It should match the expected value, in which case you are ready to move on to the next chapter.
