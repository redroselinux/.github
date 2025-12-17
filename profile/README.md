<h1 align="center">
  <img width="32" height="32" alt="image" src="https://github.com/user-attachments/assets/2ae22b1a-0162-43c7-b522-c741fabbb9fb" />
  Redrose Linux
</h1>
<p align="center">
  <code>Redrose aims to make Linux more beautiful, functional, and simple.</code>
</p>

Redrose Linux is an Arch-based project focused on unifying beauty, usability, and simplicity across the Linux experience - from the shell to the desktop environment. This distro has a custom package manager that does not use the base of pacman. Later, we will turn into an independent distro, but the beta uses Arch.
<details> <summary>
  🏗️ Roadmap
</summary>

- 🏗️ Ostre - the custom Linux shell for Redrose
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
- ✅ Car - the replacement of pacman in Redrose (will support pacman repos through conversion, not makepkg)
  - https://redroselinux.github.io/car-package-viewer
- 🏗️ RedRepro - a tool for more advanced system repro
  - [ ] integrate with car repro
  - [ ] other package managers
  - [ ] configs
  - [ ] browser data 
- 🏗️ Redrose Linux
  - [ ] use car
  - [ ] use umbrella
  - [ ] installer
</details>
<details>
<summary>📜 License</summary>

Redrose Linux is licensed under the **GNU General Public License v3.0 (GPLv3)**.

**Exceptions:**
- [umbrella](https://github.com/redroselinux/umbrella) - licensed under the [Unlicense](https://unlicense.org/).
- [crust](https://github.com/redroselinux/crust) - licensed under the [MIT License](https://github.com/redroselinux/crust/blob/main/LICENSE) **with minor edits**.
- this list is not updated as often. always check licenses
- Third-party software included in Redrose Linux retains its original license terms.
- If not stated, the license is GPLv3.

</details>
