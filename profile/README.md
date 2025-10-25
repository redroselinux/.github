<h1 align="center">
  <img width="40" height="40" src="https://github.com/user-attachments/assets/0b917dc4-5b9f-412e-a244-e8ec0eb58c1a" alt="logo" />
  Redrose Linux
</h1>
<p align="center">
  <code>Redrose aims to make Linux more beautiful, functional, and simple.</code>
</p>

Redrose Linux is an Arch-based project focused on unifying beauty, usability, and simplicity across the Linux experience - from the shell to the desktop environment. This distro has a custom package manager that does not use the base of pacman.
<details> <summary>
  🏗️ Roadmap
</summary>

- ✅ Crust - our interactive Linux shell, currently wrapping around Bash
  - `yay -S crust-git`
  - `pip install crust-shell` / to install globally: `--break-system-packages` 
- 🏗️ Ostre - the replacement of Bash in Crust
  - [ ] never require shift
  - [ ] syntax like: .p instead of |
-  🏗️ i4 - a DE on top of i3
    - [ ] settings app
      - [x] modifier set
      - [ ] displays
      - [x] network
      - [x] disks overview
      - [x] wallpaper 
    - [ ] lock screen
    - [ ] widgets
- ✅ Umbrella - intelligent corrections like what package to install to fix an issue
  - [x] autocorrect package
  - [x] package not found - suggest install command 
- 🏗️ Car - the replacement of pacman in Redrose (will support pacman repos through conversion, not makepkg)
  - https://redroselinux.github.io/car-package-viewer
  - [x] basic features
  - [x] mirrors
  - [ ] threading for speeeed
  - [ ] all important packages included
    - build gcc
    - build coreutils
  - [ ] stable (Redrose Flower), rolling (Redrose Tree)
  - [ ] integrate as main pm for the archiso profile (somehow?)
  - [x] package repro
- 🏗️ RedRepro - a tool for more advanced system repro
  - [ ] integrate with car repro
  - [ ] other package managers
  - [ ] configs
  - [ ] browser data 
- 🏗️ Redrose Linux - an Arch-based Linux distro using our projects
  - [ ] use crust
  - [ ] use car
  - [ ] use umbrella
  - [ ] calamares installer
  - [x] graphical interface in live
