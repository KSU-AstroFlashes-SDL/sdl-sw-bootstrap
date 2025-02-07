# KSU AstroFlashes SDL Software Team Bootstrap Scripts

This is a collection of "bootstrap" scripts to assist Software Team
members in the installation and configuration of software development
prerequisistes and utilities.

## Windows

Team members running Microsoft Windows SHOULD install the Windows Subsystem for Linux (Ubuntu distribution) and Microsoft VS Code.

* https://learn.microsoft.com/en-us/windows/wsl/install
* https://code.visualstudio.com/download

Once these have been installed, git clone this repository into Ubuntu and run the wsl-ubuntu-bootstrap script:

```bash
$ git clone https://github.com/KSU-AstroFlashes-SDL/sdl-sw-bootstrap
$ cd sdl-sw-bootstrap
$ ./wsl-ubuntu-bootstrap | tee wsl-ubuntu-bootstrap.log

