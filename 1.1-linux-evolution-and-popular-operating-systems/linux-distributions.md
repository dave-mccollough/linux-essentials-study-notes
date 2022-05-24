# Linux Distributions

## Distribution:
A collection of components that form a system.  A disribution is comprised of the following:
- Linux Kernal
- GNU Core
- X Server (Optional)
- Graphic Interface (Optional)
- **Distribution release version:**  `lsb_release -a` 

## Linux Kernal:
The Linux kernal is the foundation of the operating system.  It is free and open-source.  It connects the application layer to the hardware layer.  Hardware is incorporated into the file heirarchy through the `/dev` and `/sys` directories, and process information is mapped in `/proc`.
- **Kernal version:**  `uname -r` 

## GNU Core:
The GNU Core are the basic file, shell and text manipulation utilities of the GNU operating system.  These utitlies are expected to exist on every operating system.
- **GNU Core Utilities Version version:**  `ls --version` 

## X Server:  
Display server for the X Windows system; a framework for a GUI enviornment.  X is an architecture agnostic framework for remote graphic user interfaces and input devices.  Designed to be used over network connections.
- **GNU Core Utilities Version version:**  `sudo X -version`  (need to elevate permissions to run command `sudo`)

## Graphic Interface:
Desktop enviornment.  Allows users the ability to navigate the operating system with using a mouse.  Common Linux desktops include Gnome, KDE, Unity, Cinnamon, MATE, and Xfce.






