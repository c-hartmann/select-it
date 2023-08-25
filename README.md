# Toogle Dolphin Selection Mode

A KDE 5 dolphin context menu extension (aka Service Menu), that let's you
toggle Dolphins Selection Mode as with the 'Shift' key via D-Bus from within
the context menu for folders.

This is for lazy people as me, who want to save the long move with their
pointing device to the "View" menu and "Select Files and Folders" from
within there or do not know about 'Shift' keyboard shortcut.

After Installation this new action should be available in top level of the
context meneu. (if more than one action applies to directories, it will be
located under "Actions").

This is a clean room implementation based on D-Bus, therefore it lacks any
dependencies beside qdbus(1), that should come basicly always with KDE.
