#### Magisk GCam Patch

Fix slow motion & 60fps not working on Google camera.

This module could work on most of the devices. Actually, this module is mostly for non-nexus devices, which is considered not supported by Google Camera. By default, other devices can't even open slomo and they will expect ANR immediately. This module fixes some missing media profiles and makes slomo working again. The basic logic is simple, Nexus devices won't need such kind of module.

#### NOTICE

* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.
* Enable HAL3 with uncommenting `persist.camera.HAL3.enabled=1` in /sbin/.core/img/gcam-patch/system.prop if you meet any problem when using this module. The differences between every two devices are huge and I can't promise that this module must work for you. If you know how to patch your device, please tell me.
* Recent fixes:
Magisk v15 Template 1500 compatabilities

#### Credit & Support

* Copyright (C) 2017 simonsmh <simonsmh@gmail.com>
* Any issue or pull request is welcomed.
* Star this module at [GitHub](https://github.com/Magisk-Modules-Repo/magisk-gcam-patch).
