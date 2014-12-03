---
layout: default
title: "Fixing Eclipse in KEC 123"
---

Following the recent Java update to campus PCs, Eclipse no longer starts in KEC 123.  However, you can create a new (working) shortcut to it as follows.

In the Start menu, choose **All Programs&rarr;Eclipse**, then right-click on the Eclipse shortcut, and choose **Send to&rarr;Desktop (create shortcut)**.  You should now have an Eclipse shortcut on your desktop.

Right click on the Eclipse shortcut on the desktop and choose **Properties**.  Change the Target to the following:

    "C:/Program Files/eclipse/eclipse.exe" -vm "C:/Program Files/Java/jdk1.8.0_05/bin/javaw.exe"

Click **Apply**, then **Ok**.

Double-clicking the Eclipse shortcut on the Desktop should now start Eclipse as normal.
