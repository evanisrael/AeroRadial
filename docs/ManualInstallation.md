---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.2.0.0
AeroRadial (DAR)
created: 17 Feb 2022
updated: 13 Apr 2023

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

## [AeroRadial (DAR)][mod]

[Home](./index.md)

This part add-on adds two (2) electric charge producing parts

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `DaMichel` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/AeroRadial`
* Extract the package's `DaMichel` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/DaMichel` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/AeroRadial`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/AeroRadial`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/AeroRadial`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [DaMichel]
      + [DaMichelLtd][DML]
        + [Agency]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        ...
      + [AeroRadial][mod]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * AeroRadialLtd.version
        * Attributions.htm
        * CC-BY-SA-3.0.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
    ...
  * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [DaMichel Ltd (DML)][DML]

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DM/L)"
[mod]: https://www.curseforge.com/kerbal/ksp-mods/AeroRadial "AeroRadial (DAR)"

THIS FILE: CC BY-ND 4.0 by zer0Kerbal