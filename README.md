# DemonFF 👹

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Introduction

DemonFF is a Blender addon designed to provide ease of mind by providing SA-MP functionality to Parik27s DragonFF for working with Renderware DFF files. Whether you're creating custom models or working with GTA game assets, DemonFF simplifies the process of exporting and importing DFF files.

What is a .DFF?: DFF files house object data, and are used by Renderware, as well as Rockstar itself up in most of its games since Grand Theft Auto III, until at least Grand Theft Auto IV. You'll find .DFF(Dive File Format) files in every 3D Universe GTA game you can think of. It houses the data structure for models such as buildings(has collision, mesh faces), or a "texture" of a spray tag on the side of a building(which may really be a model with empty collision, if it's not UV Mapped). .DFF files house the objects data which includes model ID, name, textures, collision, 2dfx, etc. As you can see, they're quite important.

**Note:** DemonFF is a fork of Pariks GTA DragonFF, with additions and small rewrites.

## Features

- **Renderware Compatibility**: DemonFF is tailored to work seamlessly with Renderware DFF files, offering support for various versions and features.

- **Blender Integration**: Integrate DemonFF directly into Blender, making it an integral part of your modeling and animation workflow.

- **Export and Import**: Easily export your Blender models to DFF format and import existing DFF files into Blender for further editing.

- **Collision Editing**: Streamline collision model editing with DemonFF's dedicated tools for managing spheres, boxes, vertices, and faces.

- **Custom Section IDs**: DemonFF supports Rockstar's custom section IDs, allowing you to work with specific RW plugins seamlessly.

- **SAMP/open.mp Compatibility**: DemonFF is designed for compatibility with San Andreas Multiplayer (SAMP) and open.mp, allowing you to export models and collision for use in multiplayer environments.

## Getting Started

### Installation

1. Download the latest release from the [Releases](https://github.com/spicybung/DemonFF/releases) page.
2. In Blender, go to `Edit -> Preferences -> Add-ons`.
3. Click `Install` and select the downloaded ZIP file.
4. Enable DemonFF from the list of installed addons.

### Usage

1. Open Blender and navigate to the DemonFF panel.
2. Import or create your 3D model.
3. Use DemonFF tools to edit collision models, export, and import DFF files.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Blender community and contributors.
- Inspired by the Renderware engine and GTA modding community.
- Parik27 for his DragonFF Blender Add-on, which without would have made this impossible.


---
