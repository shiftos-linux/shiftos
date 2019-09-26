# ShiftOS

Yes - you haven't lost your eyesight, or your sanity - this repo is called ShiftOS.  Originally, ShiftOS was a game made in 2014 by Philip Adams and continued on by Michael VanOverbeek from 2015 to 2017.  As a game, ShiftOS wasn't that great and its novelty wore off quickly.  However, the in-game operating system had a few neat features.  The goal of this project is to bring these features into a Linux distribution that can be used day-to-day.

### What distro is this based on?

The more familiar among you may realize that the repository's structure is that of an Arch Linux `archiso` configuration.  So, basically, that means this is another Arch-based distro.  We chose Arch due to its vast customizability, extensibility and documentation.  A lot of work will need to be done to recreate the ShiftOS experience, and a heavy-weight distro like Ubuntu would just add to this work.

### Features planned for this distribution

Most of the features in this distribution involve features from the game's in-game OS, as well as some features from the in-game operating system of **Bit Phoenix Software**'s [The Peacenet](https://github.com/bitphoenixsoftware/the-peacenet).  (We're the same people behind that.) These features include:

 - **The Shifter:** A utility allowing the creation of fully-customized system themes (gtk themes, window decorator themes, etc.) and customization of various system components (login manager, bootup splash, grub, etc.)

 - **Shiftorium:** A graphical Arch package manager and AUR helper.

 - **Skin Loader:** Allows loading of .skn files from the various iterations of the game, as well as the bundling, sharing and loading of all customizations made within the Shifter.

 - **Pong:** Can't be ShiftOS without Pong.  We're sorry.  Not really.

Along with the above ShiftOS features, the following system features will be added:

 - Bluetooth support
 - Graphical boot screen
 - Graphical Arch Linux installation utility
 - Built-in AUR helper (`yay`!)

You will also be given the ability to install additional software during setup such as:

 - LibreOffice
 - git
 - OpenSSH
 - Firefox
 - .NET Core
 - Visual Studio Code