---
author: "DjMonkey"
title: "🔃 Part Sync"
date: "2026-09-29"
description: ""
ShowToc: false
ShowBreadCrumbs: false
layout: guides-bba
---

Part Sync is a service within the application that enables you to view **high fidelity, textured,** and **lit** parts. Allowing you to preview closely what a build would actually look like in-game.

Part Sync acts upon your ***existing No Man's Sky installation***, reconstructing a compressed version of data to a centralized location on your hard disk. This means you don't have to download extra gigabytes of redistributed assets as part of the core builder app experience. Part Sync also works across future app version be using the data already cached.

When activating **Part Sync** and the **High** display setting, Part Sync runs in the background and swaps out the low quality proxy model with the higher fidelity model. There is a load time for parts being initially loaded, but once it is cached, it is instant for the future.

---

## Setting up Part Sync

![Part Sync](/images/nms-bba/guides/partsync.png)

To set up Part Sync, press the settings button at the top of the screen and configure the two paths.

PCBANKS: This is the path to your No Man's Sky installation folder. Look for the PCBANKS folder, which is usually found as `/NoMansSky/GAMEDATA/PCBANKS/`.

Cache Path: This is where the compressed assets will live, ready to be processed and loaded. You need to make sure you specify a folder that has a lot of free disk space (we are talking gigabytes).

The nature of PartSync stores a bunch of intermediate files. To free up disk space you can press the `Clear Cache` button to remove these files. This is safe to do, and does not effect the performance of already loaded parts. When running Part Sync again on unloaded parts, you will see this space fill up.

When configured correctly, you can now toggle the High option on the display settings, which will trigger Part Sync. A status bubble will appear on the top right, showing that it's working. Pressing **Shift+T** will let you toggle between Proxy and High visibility modes.

![Part Sync Status](/images/nms-bba/guides/part_sync_status.png)

Once Part Sync is done, you can enjoy your beautifully rendered bases and corvettes!

---

### Before Part Sync
<br />

![Part Sync Before](/images/nms-bba/guides/partsync_a.png)


### After Part Sync
<br />

![Part Sync After](/images/nms-bba/guides/partsync_b.png)