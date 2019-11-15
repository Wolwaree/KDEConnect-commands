# KDEConnect-commands

![GitHub repo size](https://img.shields.io/github/repo-size/guinuxbr/KDEConnect-commands)
![GitHub contributors](https://img.shields.io/github/contributors/guinuxbr/KDEConnect-commands)
![GitHub stars](https://img.shields.io/github/stars/guinuxbr/KDEConnect-commands)
![GitHub forks](https://img.shields.io/github/forks/guinuxbr/KDEConnect-commands)
![Twitter Follow](https://img.shields.io/twitter/follow/gllmarques?style=social)

Here is my `KDEConnect-commands` that allows to control your Plasma Desktop from your Android phone. It uses [KDEConnect](https://community.kde.org/KDEConnect) that is capable to do some really cool stuff. In fact, you can do almost anything like send files from and to phone, control slideshow presentation, control multimedia application, remote input and the ability to run commands directly in your Linux box.<br>

This repository contains a list of commands to be used in KDE Connect.<br>

## Prerequisites

Before you begin, ensure you have met the following requirements:
To use it, you have to install KDE Connect package on your Linux distribution and the app in your Android phone.<br>

The Android app can be found at [Google Play Store](https://play.google.com/store/apps/details?id=org.kde.kdeconnect_tp) and [F-Droid](https://f-droid.org/packages/org.kde.kdeconnect_tp/).<br>

You should have kde-connect package installed on your Linux system. In this example, I use Arch Linux.
>sudo pacman -S kdeconnect

The package have some optional dependencies (in Arch Linux) that you should install to be able to use the respective feature in KDE Connect.<br>
* sshfs: remote filesystem browser
* kde-cli-tools: configuration UI
* qt5-declarative: QML bindings
* python-nautilus: Nautilus integration

## Using KDEConnect-commands

To use KDEConnect-commands, follow these steps:
* Access KDE `System Settings` > `KDE Connect`.
* Choose your device on the list and then `Run commands`

In the window that shows up you should give a smart name and copy the command line at the column "Command".
Press "OK" and you are done.

More information about KDEConnect project can be found at [KDE Community Wiki](https://community.kde.org/KDEConnect).

## Contributing to KDEConnect-commands
To contribute to KDEConnect-commands, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin KDEConnect-commands/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Maintainer & Contributors
I'm am the only one here! Help me! :)

* [@guinuxbr](https://github.com/guinuxbr)

## Contact
If you want to contact me you can send an email to glmarques.info@gmail.com.

## License
This project uses the following license: [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.html).
