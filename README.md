This example demonstrates packaging a kivy application on Ubuntu 12.04 using PyInstaller.

The commands to install python, kivy, and pyinstaller are in `bootstrap.sh`. A Vagrantfile
is provided to make it easy to package a demo kivy app into a single-file linux executable.

Instructions:

- Install [VirtualBox](https://www.virtualbox.org/) and [Vagrant](http://www.vagrantup.com)
- `git clone https://github.com/rajbot/kivy_pyinstaller_linux_example.git`
- `cd kivy_pyinstaller_linux_example`
- `vagrant up`

Vagrant will now boot an Ubuntu 12.04 image for you, install Kivy and PyInstaller, and
create an executable that packages the kivy pong demo into a single file.
