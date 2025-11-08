---
author: "DjMonkey"
title: "⏬ Importing from No Man's Sky"
date: "2019-06-21"
description: ""
ShowToc: false
ShowBreadCrumbs: false
layout: guides-bbb
---

The way this tool interacts with No Man's Sky is through your save file by editing the parts that contain your data for bases and corvettes.

There are many options now for tools that interact with your Save file. I am using GoatFungus in my example here:

{{< tabs >}}
  {{< tab name="GoatFungus" >}}
  > Download the latest version of GoatFungus' Save Editor here: https://github.com/goatfungus/NMSSaveEditor
  
  Open the Save Editor and select the save file that contains the base you want to edit.
  
  With the save selected and loaded, go to the `Edit > Edit Raw JSON` menu option.

![alt text](/images/nms-bba/guides/guide_4.png)

In the new window you'll see a folder tree view on the left and a blank panel on the right. From the tree view you want to navigate to the following folder.

`BaseContext => PlayerStateData => PersistentPlayerBases`

Expand the `PersistentPlayerBases` folder and you will see a series of numbers starting from 0 and going up. All these numbers refer to the bases that you have made in the game. 0 being the very first base you made. It's likely your freighter base will be towards the top of this list too, and any corvettes will be here from the Voyagers update.

Selecting one of these numbers will refresh the right panel, and present to you the data for your base (in JSON format). You can identify the base by it's name, by looking for the "Name" field.

![alt text](/images/nms-bba/guides/guide_3.png)

  {{< /tab >}}
{{< /tabs >}}



Once you've correctly identified your base using any of these tools. You need to select the entire chunk of text that is displayed for that base. You can do this by using the Ctrl+A system hotkey.

Copy this text into your clipboard (Ctrl+C).

Now it's time to bring it into Blender. In the side bar for the add-on - select "Import NMS". This will directly load in the base from your clipboard into the Blender scene.

![alt text](/images/nms-bbb/guides/guides2.png)

That's it! Your base or corvette should now display in Blender.

To make edits and bring this back into the game - check out the [Exporting to NMS](/no-mans-sky-base-builder-blender/guides/exporting-to-nms/) page for more details.