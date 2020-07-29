# Welcome to potato linux!
Potato linux is an operating system build up on the linux kernel. With it come many advantages, like drivers and controll modules for potato mashers.
# The kernel.
As stated above, potato linux runs under the linux kernel. This however was modified and is now called potatonix
## Pre included kernel drivers and modules.
Potato linux and its potatonix kernel includes alot of custom made modules and drivers, here are a few of them. You can list all of them by using the pomd utility in a tty or in a desktop terminal called poterm
* poultra: Kernel driver that supports most of the potato mashers available on the market that can connect via an usbA port.
* powin: A module that allows translation of windows executables without a need of wine.
* powinrr: Screen reading module for windows applications, build from the nvda base and modified to work with the linux and potatonix kernels.
# potato package manager
The potato package manager, formerly known as potatopkg, is a really nice and user friendly package manager, focusing on stability, flexibility and responsivness.
The potatopkg package manager is primarily build to work with potato linux, however if compiled from source and modified accordingly it can work on a variety of systems, including debian, windows, and arch linux.
## Potato builders database
The potato builders database, formerly known as the pbd, is an community driven database of files that define how certain package is build, like arch linux's arch user repository/aur. Unlike pacman in arch linux, potatopkg has a buildin support for pbd, so one can just run "potatopkg install checkra1n" And if checkra1n is not available in the official repositories it wil ask "This package is not available in the available repositories on this system, however we have found it in pbd. Build from pbd? Y/N" And the user wil have a choice.
# PoDE, A modern desktop!
PoDE is a flexible, fast and lightweit desktop enviromment, desighned for potato linux! With PoDE you'll do more, and suffer less. PoDE's automatic system and resource manager wil take care of all system processes, and you'll decide if it kills the unused ones, or if it keeps them running. in the advanced PoDE setup app.
## Poterm
Poterm is a lightweit terminal made for PoDE. Now using the shell wil be much easier! With the potatosh and poterm, you wil feel like in heaven! Easy navigation between your terminal tabs wil let you run multiple processes and check on them when necessary at any time! Poterm also supports a variety of options, including black/white only terminals, an ability to enable a tiling mode, and many more!
## pomg
PoMG is a gui applicattion desighned to manage processes. But, its more than that! Its also a system maintenance utility, and it can make tasks you shedule in PoDE setup! Clear the cache, uninstall unused applications and packages, remove junk files, and many more! PoMG also serves as a gui frontent for the potatopkg package manager
# potatoctl
potatoctl is a heard command of potato os. It controlls the init system called openpotato. 
## Main controll commands.
* info ps-name: Checks the information about the potato service/ps
* enable ps-name: Enables a potato service/ps
* disable ps-name: Disables a potato service/ps
* start ps-name: Starts a potato service/ps
* stop ps-name: Stops a potato service/ps
# openpotato
openpotato is an init system used by potato linux. This init system is literally a fork of systemd with only the title and manager commands changed, so just look at the systemd manual because i'm too lazy to thing of any crazy made up shit to write in here.
# Support for potatoam64!
Potato linux desighners created this innovative architecture, potatoam64! Its just arm with a changed title. Oops, that shouldn't be there.
Copyright 2020 Potato makers inc, all rights reserved.
