---
author: "DjMonkey"
title: "⏬ Importing from No Man's Sky"
date: "2019-06-21"
description: ""
ShowToc: false
ShowBreadCrumbs: false
layout: guides-bba
---

The way this tool interacts with No Man's Sky is through your save file by editing the parts that contain your data for bases and corvettes.

There are many options now for tools that interact with your Save file. I am using GoatFungus in my example here:

{{< include "includes/saveeditor.md" >}}

Once you've correctly identified your base using any of these tools. You need to select the entire chunk of text that is displayed for that base. You can do this by using the Ctrl+A system hotkey.

Copy this text into your clipboard (Ctrl+C).

Now it's time to bring it into the App, from the File menu at the top left, select "Import from NMS...".

![alt text](/images/nms-bba/guides/guide_5.png)

In the new panel that appears, paste the JSON text into the empty text box, and then press Import. From here you also have the option of whether to create a new tab for this data.

![alt text](/images/nms-bba/guides/guide_6.png)

That's it! Your base or corvette should now display in the tool.

To make edits and bring this back into the game - check out the [Exporting to NMS](/no-mans-sky-base-builder-app/guides/exporting-to-nms/) page for more details.