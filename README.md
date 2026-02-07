# Extensive Morphe & Revanced Builder
[![CI](https://github.com/sixstrings/morphe-revanced-builder/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/sixstrings/morphe-revanced-builder/actions/workflows/ci.yml)
[![GitHub License](https://img.shields.io/github/license/sixstrings/morphe-revanced-builder?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fsixstrings%2Fmorphe-revanced-builder%2Fblob%2Fmain%2FLICENSE)](https://github.com/sixstrings/morphe-revanced-builder/blob/main/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/sixstrings/morphe-revanced-builder/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fsixstrings%2Fmorphe-revanced-builder%2Freleases)](https://github.com/sixstrings/morphe-revanced-builder/releases)

This Morphe and Revanced builder creates both APKs and [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules for [ReVanced](https://github.com/revanced) and [Morphe](https://github.com/MorpheApp) versions of YouTube and YouTube Music.

#### **Get the latest CI release [here](https://github.com/sixstrings/morphe-revanced-builder/releases/latest).**

## Installation
### Non-root users
- Install the [ReVanced GmsCore app](https://github.com/ReVanced/GmsCore/releases/latest) or the [Morphe MicroG-RE app](https://github.com/MorpheApp/MicroG-RE).
- Download the APK files you want to install from the [releases page](https://github.com/sixstrings/morphe-revancec-builder/releases/latest).

### Root users
- Download the ZIP files you want to flash from the [releases page](https://github.com/peternmuller/revanced-morphe-builder/releases/latest).
  
## Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube and YouTube Music from the Play Store.


## If you are having trouble with the classic mount method of the modules such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps you can consider using
- [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

## Building Locally
### On Termux
```bash
bash <(curl -sSf https://raw.githubusercontent.com/peternmuller/revanced-morphe-builder/main/build-termux.sh)
```
### On Desktop
```bash
git clone https://github.com/peternmuller/revanced-morphe-builder
cd revanced-morphe-builder
./build.sh
```

## Credits
- [j-hc](https://github.com/j-hc) for creating this builder, for zygisk-detach and rvmm-zygisk-mount.
- Of course the [Morphe](https://github.com/MorpheApp) team for the amazing Morphe app and patches.
- The [ReVanced](https://github.com/ReVanced) team for Revanced app.
- [peternmueller](https://github.com/peternmueller/revanced-morphe-builder) for the fork.

## License
    Copyright (C) 2024-2026  Peter Noël Muller

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
