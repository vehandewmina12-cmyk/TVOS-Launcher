# tvOS 27-style Android TV Launcher

Open this folder in Android Studio (Koala or newer), let Gradle sync, then Build > Build APK(s).
Install on the box, press Home and choose "tvOS Launcher" as the default.

* Left click  = open app (hover moves the focus highlight)
* Right click = back (returns to the first icon)
* "Antenna TV" button = opens the box's tuner / TV app.
  If not found it asks you to choose the TV app; long-press the button any time to change it.
  Find your box's TV app package:  adb shell pm list packages | grep -i -E "tv|source"
