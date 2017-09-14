# About
This repository contains a patch for GNAT Programming Studio 2017 which enables
it to compile code suitable for the Nucleo-F030R8 board.

# Requirements
* GPS2017
* git

# How To Use
* go into your GPS2017 directory
* copy the patch there
* run `git apply 0001-Modified-rts-sources-to-fit-into-an-stm32f030r8.patch`
* (re)build the BSPs from the bb-runtimes repository
* now when compiling with the ravenscarp-sfp-nucleo-f030r8, the rts will fit
  into the flash and ram
