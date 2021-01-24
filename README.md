# Welcome to LZDoom!

[![Build Status](https://ci.appveyor.com/api/projects/status/github/drfrag666/gzdoom?branch=g3.3mgw&svg=true)](https://ci.appveyor.com/project/drfrag666/gzdoom) [![Build Status](https://travis-ci.org/drfrag666/gzdoom.svg?branch=g3.3mgw)](https://travis-ci.org/drfrag666/gzdoom)

## LZDoom is a fork of GZDoom 3.3 compiling with MinGW and running on older non SSE2 cpus while keeping the DDRAW and D3D backends for compatibility.

Copyright (c) 1998-2019 ZDoom + GZDoom teams, and contributors

Doom Source (c) 1997 id Software, Raven Software, and contributors

Please see license files for individual contributor licenses

Special thanks to Coraline of the 3DGE team for allowing us to use her README.md as a template for this one.

### Licensed under the GPL v3
##### https://www.gnu.org/licenses/quick-guide-gplv3.en.html
---

## How to build GZDoom

For Ubuntu 18.04 - 20.04 on Arm processors like the rk3326:
```apt-get install g++ make cmake libsdl2-dev git zlib1g-dev
libbz2-dev libjpeg-dev libfluidsynth-dev libgme-dev libopenal-dev
libmpg123-dev libsndfile1-dev libgtk-3-dev timidity nasm
libgl1-mesa-dev tar libsdl1.2-dev libglew-dev
```

```bash
git clone https://github.com/christianhaitian/lzdoom.git
cd lzdoom
mkdir build
cd build
cmake ../.
make (or use make -j2 or -j3 if you have the additional core and memory to handle this to speed up the build)

```

For other platforms:
To build GZDoom, please see the [wiki](https://zdoom.org/wiki/) and see the "Programmer's Corner" on the bottom-right corner of the page to build for your platform.

GZDoom repo: https://github.com/coelckers/gzdoom

## Other forks/branches

 - legacy: Official GZDoom vintage build for GL 2 hardware. - gzdoom32: ZDoom32. - gzdoomle: ZDoom LE (Legacy Edition).
For more info see old README.md: https://github.com/drfrag666/gzdoom/blob/gzdoom32/README.md
