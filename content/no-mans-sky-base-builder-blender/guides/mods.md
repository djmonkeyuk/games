---
author: "DjMonkey"
title: "🪛 Mod Support"
date: "2019-06-21"
description: ""
ShowToc: false
ShowBreadCrumbs: false
layout: guides-bbb
---

The Blender add-on is designed towards supporting the vanilla game as much as possible, however, any additional base parts introduced by mods will display as cubes but will still be able to import/export to the game.

You can introduce your own FBX files by adding them to your user directory folder. The layout for this should be…

* %USERPROFILE%/NoMansSkyBaseBuilder/
  * mods/
    - mod_name/
      - models/
        - category/
          - **MOD_WALLA.fbx**
          - **MOD_WALLB.fbx**
        - category_b/
          - **MOD_FLOORA.fbx**
          - **MOD_FLOORB.fbx**

The names of categories are up to the user.

The FBX file name should reflect the name of the part in-game.
