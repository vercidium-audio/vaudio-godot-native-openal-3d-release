# Vercidium Audio (Native)

Raytraced audio GDExtension with realistic muffling, reverb, ambience and visualisation for non-Mono Godot 4, using OpenAL Soft as the audio backend.

> [!WARNING]
> This repository contains plugin releases. For source code, see [vaudio-godot-native-openal-3d-source](https://github.com/vercidium-audio/vaudio-godot-native-openal-3d-source).

For Mono Godot (C#), please use [this plugin](https://github.com/vercidium-audio/vaudio-godot-mono-openal-3d/releases).

This repository requires the Vercidium Audio v1.8.1 SDK to run. Windows, Linux and macOS (Apple Silicon) are supported. OpenAL Soft is bundled.
- Download the Vercidium Audio SDK from [vercidium.com](https://vercidium.com)

> Please note that the Vercidium Audio SDK is not free for commercial use. See [vercidium.com/eula](https://vercidium.com/eula)

## Features

- Muffle sounds in real time
- Accurate reverb in any environment
- Innovative event-based raytracing system
- Realistic energy-based model using materials
- Dynamic scene updates - automatically handles moving objects

## References
- [Source repo](https://github.com/vercidium-audio/vaudio-godot-native-openal-3d-source)
- [Vercidium Audio documentation](https://vercidium.com/docs)

## Installation

1. Clone or download this repository into your Godot project's `addons/vaudio-godot-native-openal-3d/` folder
2. From the Vercidium Audio SDK, copy the vaudionative library for your platform into `addons/vaudio-godot-native-openal-3d/bin/`:
   - Windows: `vaudionative.dll` + `glfw3.dll` (from `native/dev/windows`)
   - Linux: `libvaudionative.so` (from `native/production/linux`)
   - macOS (Apple Silicon): `libvaudionative.dylib` (from `native/production/mac`)
3. Open your project in Godot — the GDExtension loads automatically, no plugin activation step required

OpenAL Soft (`soft_oal.dll` / `libopenal.so.1` / `libopenal.1.dylib`) is bundled in `bin/` already.

## Licencing

The Vercidium Audio SDK is free for non-commercial products only. To purchase a licence for commercial use, head over to the [Vercidium Audio website](https://vercidium.com).

This plugin uses OpenAL Soft, which is licensed under LGPL v2.1. Source is available at https://github.com/kcat/openal-soft.