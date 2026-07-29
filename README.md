# Vercidium Audio (Native)

Raytraced audio plugin with realistic muffling, reverb, ambience and visualisation for Godot 4 —
native GDExtension build for non-Mono ("Native Godot") projects, using OpenAL Soft as the audio
backend.

> [!WARNING]
> This plugin is experimental and requires much testing and feedback

This repository requires Vercidium Audio v1.5.0 and OpenAL Soft to run:
- Download the Vercidium Audio SDK from [vercidium.com](https://vercidium.com) and place
  `vaudionative.dll` in this addon's `bin/` folder
- Download the OpenAL Soft DLL from
  [github.com/kcat/openal-soft](https://github.com/kcat/openal-soft/releases/tag/1.25.2) and
  place `soft_oal.dll` in this addon's `bin/` folder

> Please note that the Vercidium Audio SDK is not free for commercial use. See
> [vercidium.com/eula](https://vercidium.com/eula)

## Installation

1. Clone or download this repository into your Godot project's `addons/vaudio-godot-native-release/`
   folder
2. Add `vaudionative.dll` and `soft_oal.dll` to `addons/vaudio-godot-native-release/bin/` (see
   above)
3. Open your project in Godot — the GDExtension loads automatically, no plugin activation step
   required

Setup instructions are also [available here](https://vercidium.com/docs/godot/getting-started).

## References
- [Source repo](https://github.com/vercidium-audio/vaudio-godot-native-source)
- [Vercidium Audio documentation](https://vercidium.com/docs)

## Licencing

The Vercidium Audio SDK is free for non-commercial products only. To purchase a licence for
commercial use, head over to the [Vercidium Audio website](https://vercidium.com).
