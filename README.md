# kicad-parts

A personal collection of KiCad footprints/symbols/3D models for my PCB projects.

## Usage

Clone this repo into a directory named `extra-parts` in your KiCad project's top level directory.
It's unfortunate that this is necessary, but as of KiCad 6, relative paths are not supported for
3D models referenced from footprint files.

https://forum.kicad.info/t/best-way-to-share-footprints-with-3d-model/26743/36

Example:

```
some_kicad_project
├── README.md
├── extra-parts
│   ├── kicad-parts
│   │   ├── <stuff from this repo>
├── some_kicad_project.kicad_pcb
├── some_kicad_project.kicad_pro
├── some_kicad_project.kicad_sch
```
