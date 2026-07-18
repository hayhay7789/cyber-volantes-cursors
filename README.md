# Cyber-Volantes Cursors (Dark)

A combination of Volantes cursors with the Cyberpunk 2077 loading animation featured in the Daemon 2.0 Plasma theme. 

These are fully animated at 24fps and available in 64px, 48px, 32px, or 24px sizes.

Only available for Dark theme.

#### Differences from source

The progress and wait cursors (animated loading cursors) have had their animations replaced with the Cyberpunk 2077 loading animation (pictured).

![Cyberpunk Loading Animation Preview](./src/assets/loading-animation.gif)
![Cyberpunk Loading Animation Preview](./src/assets/progress-animation.gif)

## Install

The following are the manual installation instructions from the original project, which should work just the same for this fork.

Available here for download: https://www.opendesktop.org/p/2365992/


1. Install dependencies:

    - git
    - make
    - inkscape
    - xcursorgen
    
Fedora:

    ```
    sudo dnf install git make inkscape xcursorgen
    ```

Ubuntu:

    ```
    sudo apt install git make inkscape xcursorgen
    ```

2. Run the following commands as normal user:

    ```
    git clone https://github.com/varlesh/volantes-cursors.git
    cd volantes-cursors
    make build
    sudo make install
    ```

3. Choose a theme in the Settings or in the Tweaks tool.

If the build is not working for you, and you don't want to use the Pling version, the compiled X11 cursors (progress and wait) are included in the main folder. Therefore, you can easily copy them to your existing cursor folder (for me, found under ~/.icons/volantes_cursors/cursors) to perform a drag-and-drop manual installation.

To make your system look even more Cyberpunk, the [Daemon 2.0](https://github.com/MathisP75/daemon-kde-mk2) Plasma theme and colour scheme looks amazing with these cursors.

#### License & Attributions

This project is a customized fork of the original [Volantes Cursors](https://github.com/varlesh/volantes-cursors), which was originally licensed under GPL-2.0-or-later. 
To accommodate the GPL-3.0 licensed image assets, and as permitted by the original project's "or later" clause, this entire modified repository is now distributed under the [GNU General Public License v3.0](LICENSE).

#### Third-Party Assets
* **Images & Graphics:** Sourced from [Daemon 2.0](https://github.com/MathisP75/daemon-kde-mk2), which is licensed under the GPL-3.0. 
