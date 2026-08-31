# Vercidium Audio (Native)

Raytraced audio GDExtension with realistic muffling, reverb, ambience and visualisation for non-Mono Godot 4, using OpenAL Soft as the audio backend.

> [!WARNING]
> This repository contains plugin releases. For source code, see [vaudio-godot-native-openal-3d-source](https://github.com/vercidium-audio/vaudio-godot-native-openal-3d-source).

For Mono Godot (C#), please use [this plugin](https://github.com/vercidium-audio/vaudio-godot-mono-openal-3d/releases).

This repository requires Vercidium Audio v1.8.0 and OpenAL Soft to run:
- Download the Vercidium Audio SDK from [vercidium.com](https://vercidium.com)
- Download the OpenAL Soft DLL from [github.com/kcat/openal-soft](https://github.com/kcat/openal-soft/releases/tag/1.25.2)

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
2. Copy `vaudionative.dll` and `glfw3.dll` from the Vercidium Audio SDK `native/dev/windows` folder, to the `addons/vaudio-godot-native-openal-3d/bin/` folder
3. Copy `soft_oal.dll` from the OpenAL Soft download, to the `addons/vaudio-godot-native-openal-3d/bin/` folder
4. Open your project in Godot — the GDExtension loads automatically, no plugin activation step required

## Licencing

The Vercidium Audio SDK is free for non-commercial products only. To purchase a licence for commercial use, head over to the [Vercidium Audio website](https://vercidium.com).

This plugin uses OpenAL Soft, which is licensed under LGPL v2.1. Source is available at https://github.com/kcat/openal-soft.