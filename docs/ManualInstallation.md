---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
6S Service Compartment Tubes (SCT)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# 6S Service Compartment Tubes (SCT)

[Home](./index.md)

It's a tube.. and a hull... and a cargo bay... and a.. well, just about everything. And it is only 2 PARTS!!! For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `BingoAerospace` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BingoAerospace/ServiceCompartmentTubes`
* Extract the package's `BingoAerospace/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/BingoAerospace` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/BingoAerospace/ServiceCompartmentTubes`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BingoAerospace/ServiceCompartmentTubes`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/BingoAerospace/ServiceCompartmentTubes`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [BingoAerospace]
      + [ServiceCompartmentTubes]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-SA-4.0.txt
      * changelog.md
        ManualInstallation.htm
      * readme.htm
      * ServiceCompartmentTubes.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Bingo Aerospace (BA)][BA]

[BA]: https://forum.kerbalspaceprogram.com/index.php?/topic/209841-*/ "Bingo Aerospace (BA)"