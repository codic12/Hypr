![Hypr](https://i.imgur.com/LtC153m.png)

![BuildStatus](https://github.com/vaxerski/Hypr/actions/workflows/c-cpp.yml/badge.svg)
![Issues](https://img.shields.io/github/issues/vaxerski/Hypr)
![PRs](https://img.shields.io/github/issues-pr/vaxerski/Hypr)
![Lang](https://img.shields.io/github/languages/top/vaxerski/Hypr)
![License](https://img.shields.io/github/license/vaxerski/Hypr)
![Best](https://img.shields.io/badge/Standard-C%2B%2B20-success)
![HiMom](https://img.shields.io/badge/Hi-mom!-ff69b4)
<br/><br/>
Hypr is a Linux tiling window manager for Xorg. It's written in XCB with modern C++ and aims to provide easily readable and expandable code.

Hypr needs testers! Check it out and report suggestions or bugs!
<br/>

# Key Features
- True parabolic animations
- Rounded corners and borders
- Config reloaded instantly upon saving
- A built-in status bar with modules
- Easily expandable and readable codebase
- Multiple tiling modes (dwindling and master)
- Keybinds config
- Tiling windows
- Floating windows
- Workspaces
- Moving / Fullscreening windows

# Configuring
See the [Wiki Page](https://github.com/vaxerski/Hypr/wiki/Configuring-Hypr) for a detailed overview on the config, or refer to the example config in examples/hypr.conf.

To use a custom config, place it in ~/.config/hypr/hypr.conf

# Screenshot Gallery

![One](https://i.imgur.com/WJhbvij.png)
![Two](https://i.imgur.com/B0MDTu2.png)
![Three](https://i.imgur.com/yvZVde7.png)

# Building
See the [Wiki](https://github.com/vaxerski/Hypr/wiki/Building) to see build instructions.

# Known issues
- Picom's shadow and effects do not update for cheap animations while animating
- Non-cheap animations are choppy (duh!)
- The config is still pretty simple, although riceable!
- Popups sometimes are created pretty small

# Contributions
Refer to [CONTRIBUTING.md](https://github.com/vaxerski/Hypr/blob/main/CONTRIBUTING.md) and the [Wiki](https://github.com/vaxerski/Hypr/wiki/Contributing-&-Debugging) for contributing instructions and guidelines.
