---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
LanderTek (LTEK)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# LanderTek (LTEK)

[Home](./index.md)

<BLURB>

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the AxialAerospace/LanderTek folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/LanderTek`
* Extract the package's `AxialAerospace` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/AxialAerospace` --> `<KSP_ROOT>/GameData/AxialAerospace`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/LanderTek`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AxialAerospace/LanderTek`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/AxialAerospace/LanderTek`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [AxialAerospace]
      + [LanderTek]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * changelog.md
        * GPLv3.txt
        * readme.htm
        * LanderTek.version
    ...
    * [Module Manager][mm] or [Module Manager /L][mml]
  * KSP.log
  ...
```

### Dependencies

* *either*
  * [Firespitter core][fsc]
  * [Firespitter][fs]
* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]

[LTEK]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-* "LanderTek (LTEK)"
[fs]: https://github.com/snjo/Firespitter "Firespitter"
[fsc]: https://github.com/snjo/Firespitter "Firespitter core"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
