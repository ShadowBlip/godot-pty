# Godot PTY

Godot PTY is a native GDExtension for Godot 4.x that allows you to create, run,
and interact with processes in a pseudo terminal (PTY). You can directly read
from the stdout and write to the process's stdin.

## Requirements

### Build Requirements

The following are required to build Open Gamepad UI:

- Godot 4.x
- GCC 7+ or Clang 6+.
- Python 3.5+.
- SCons 3.0+ build system
- pkg-config (used to detect the dependencies below).
- X11, Xcursor, Xinerama, Xi and XRandR development libraries.
- MesaGL development libraries.
- ALSA development libraries.
- PulseAudio development libraries.
- make (optional)
- unzip (optional)
- wget (optional)

If you are using ArchLinux, you can run the following:

```bash
pacman -S --needed scons pkgconf gcc libxcursor libxinerama libxi libxrandr mesa glu libglvnd alsa-lib pulseaudio make unzip wget git
```

## Building

You can build the project using the following:

```bash
make build
```

## Usage

Copy the `addons` folder after you have built the project into your Godot
project directory.
