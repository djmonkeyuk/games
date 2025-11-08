---
author: "DjMonkey"
title: "🛠️ Manipulation Tools"
date: "2019-06-21"
description: ""
ShowToc: false
ShowBreadCrumbs: false
layout: guides-bba
---

## Transformation

There are three main tools for building bases in a 3D tool environment. You may be already familiar with some of them because they already kinda exist in the game

* `Translation` - The act of moving a 3D object into a different position. This is done by changing their Translate X, Y and Z values.

* `Rotation` - The act of rotating a 3D object into a different angle. This is done by changing their Rotate X, Y  and Z values.

* `Scale` - The act of making a 3D object smaller or larger. In No Man's Sky we are only focussing on one scale value.

When selecting an object in the tool, a "gizmo" will appear to make it easier to change these Translation, Rotation and Scale values. You are able to click and drag different parts of the gizmo to affect each channel.

![alt text](/images/nms-bba/guides/guide_9.png)

You can change which transform mode you are in by clicking the buttons found at the top of this tool, or using the W, E and R hotkeys.

---

## Grid Snapping

We can further refine how our objects Translate and Rotate by using the "Grid Snapping" settings found in the tool bar at the top of the screen.

Changing these values will affect the interval steps when using each manipulator. For example, when rotating an object the default step is 45 degrees. You can change this value or disable it completely if you chose.

---

## Manipulation Space

In addition to these tools, we can also change HOW the gizmo affects the part by changing what "space" they are in. The two spaces we can work on are "local" and "global".

* `Local` - This will move the piece relative to it's current position. For example, if the part is rotated 45 degrees to the side, if we move the piece upward it will move diagonally along that 45 degree direction.

* `World` - This will move the piece relative to the world (or planet). For example, if the part is rotated 45 degrees to the side, if we move the piece upward it will IGNORE the angle, and move it directly upwards in a completely verticle direction.

You can toggle the space by pressing T, or using the button found in the top bar in the application.

![alt text](/images/nms-bba/guides/guide_10.png)