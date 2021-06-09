# Horus

[![R&D](https://img.shields.io/badge/-R%26D-brightgreen.svg)](https://github.com/bqlabs/horus)
[![License](http://img.shields.io/:license-gpl-blue.svg)](http://opensource.org/licenses/GPL-2.0)
[![Documentation Status](https://readthedocs.org/projects/horus/badge/?version=release-0.2)](http://horus.readthedocs.io/en/release-0.2/?badge=release-0.2)

Horus is a general solution for 3D laser scanning. It provides graphic user interfaces for connection, configuration, control, calibration and scanning with Open Source [Ciclop 3D Scanner](https://github.com/bqlabs/ciclop).

This is a research project to explore the 3D laser scan with free tools. Feel free to use it for experiments, modify and adapt it to new devices and contribute new features or ideas.

This project has been developed in [Python](https://www.python.org/) language and it is distributed under [GPL v2](https://www.gnu.org/licenses/gpl-2.0.html) license.

**This fork will be a Python 3.x port. Have fun!**

## Installation

### CAUTION
This Python 3.x port is currently unstable.

### With Python 3.8.x

* 0. [Install Python 3.8.x](https://www.python.org/downloads/) and [Arduino Drivers](https://www.arduino.cc/en/software) ([if needed](https://www.arduino.cc/en/Guide/DriverInstallation)).
* 1. [Download this Python 3.x port of Horus.](https://github.com/neetandgeeks/horus/archive/refs/heads/master.zip)
* 2. [Making virtual environment.](https://docs.python.org/3/tutorial/venv.html)
* 3. [Install requirements.](https://docs.python.org/3/tutorial/venv.html#managing-packages-with-pip)
* 4. Run horus.py script.

#### Example

##### on Windows like System
```bat
C:\Users\foobar> mkdir testenv &:: make your working directory
C:\Users\foobar> cd testenv &:: change current directory
C:\Users\foobar\testenv> py -3.8 -m venv horusenv &:: make your Python 3.8.x virtual environment
C:\Users\foobar\testenv> .\horusenv\Scripts\activate &:: activate virtual environment
(horusenv) C:\Users\foobar\testenv> cd ..\horus &:: change current directory to your extracted horus source
(horusenv) C:\Users\foobar\horus> py -m pip install -r requirements.txt &:: install dependencies
(horusenv) C:\Users\foobar\horus> py .\horus.py &:: run horus
```

##### on Unix like System
```console
[foobar@localhost ~]$ mkdir testenv # make your working directory
[foobar@localhost ~]$ cd testenv # change current directory
[foobar@localhost testenv]$ python3.8 -m venv horusenv # make your Python 3.8.x virtual environment
[foobar@localhost testenv]$ source horusenv/bin/activate # activate virtual environment
(horusenv) [foobar@localhost testenv]$ cd ../horus # change current directory to your extracted horus source
(horusenv) [foobar@localhost horus]$ python3 -m pip install -r requirements.txt # install dependencies
(horusenv) [foobar@localhost horus]$ python3 ./horus.py # run horus
```

## Documentation

Here you will find the official documentation of the application:

* [User's manual](http://horus.readthedocs.io/en/release-0.2/) [[es](http://horus.readthedocs.io/es/release-0.2/)]

And also all the scientific background of the project in nice Jupyter notebooks:

* [Notebooks](http://nbviewer.jupyter.org/github/Jesus89/3DScanScience/tree/master/notebooks/)
* [Repository](https://github.com/Jesus89/3DScanScience)

## Development

Horus is an Open Source Project. Anyone has the freedom to use, modify, share and distribute this software. If you want to:
* run the source code
* make your own modifications
* contribute to the project
* build packages

follow the next instructions

#### GNU/Linux

Horus has been developed using [Ubuntu Gnome](http://ubuntugnome.org/), that is based on [Debian](https://www.debian.org/), like [Raspbian](https://www.raspbian.org/), [Mint](http://linuxmint.com/), etc. All instructions provided in this section probably work for most of these systems.

* [Ubuntu development](doc/development/ubuntu.md)

NOTE: *deb* and *exe* packages can be generated in *debian like* systems

#### Mac OS X

* [Darwin development](doc/development/darwin.md)

NOTE: *dmg* packages only can be generated in Mac OS X


More interest links are shown below:

* [Presentation](http://diwo.bq.com/en/presentacion-ciclop-horus/) [[es](http://diwo.bq.com/presentacion-ciclop-horus/)]
* [3D Design](http://diwo.bq.com/en/ciclop-released/) [[es](http://diwo.bq.com/ciclop-released/)]
* [Electronics](http://diwo.bq.com/en/zum-scan-released/) [[es](http://diwo.bq.com/zum-scan-released/)]
* [Firmware](http://diwo.bq.com/en/horus-fw-released/) [[es](http://diwo.bq.com/horus-fw-released/)]
* [Software](http://diwo.bq.com/en/horus-released/) [[es](http://diwo.bq.com/horus-released/)]
* [Product documentation](http://diwo.bq.com/en/documentation-ciclop-and-horus/) [[es](http://diwo.bq.com/documentation-ciclop-and-horus/)]
* [Google group](https://groups.google.com/forum/?hl=en#!forum/ciclop-3d-scanner)

[ubuntu-logo]: doc/images/ubuntu.png
[windows-logo]: doc/images/windows.png
[macosx-logo]: doc/images/macosx.png
[debian-logo]: doc/images/debian.png
[raspbian-logo]: doc/images/raspbian.png
[fedora-logo]: doc/images/fedora.png
