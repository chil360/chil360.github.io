### ParanoidAndroid Quartz

**Download:** [pa-quartz-4-osprey-20200709-dev.zip](https://sourceforge.net/projects/chil360-android/files/pa-quartz/osprey/pa-quartz-4-osprey-20200709-dev.zip/download)

Monthly build of ParanoidAndroid Quartz including the July security patches.

**Device changes:**

Kernel:
  - defconfig: Enable Process Reclaim

Device Tree
  - Enable Zygote Pre-forking
  - Import Process Reclaim & LMK configuration from LOS and modify for Moto 8916
  - Add 0x2000U & 0x02002000U to additional gralloc usage bits
  - sepolicy: Label QTI Hostapd & Supplicant services

<hr>

### Havoc OS 3.7

**Download:** [Havoc-OS-v3.7-20200708-osprey-Unofficial.zip](https://sourceforge.net/projects/chil360-android/files/havoc-3.x/osprey/Havoc-OS-v3.7-20200708-osprey-Unofficial.zip/download)

Monthly build of Havoc updated with the July security update.
 
**Device changes:**

Kernel:
  - defconfig: Enable Process Reclaim

Device Tree
  - Enable Zygote Pre-forking
  - Import Process Reclaim & LMK configuration from LOS and modify for Moto 8916
  - Add 0x2000U & 0x02002000U to additional gralloc usage bits

<hr>

### Evolution X 10.0

Download: [EvolutionX_4.4_osprey-10.0-20200629-1058-UNOFFICIAL.zip](https://sourceforge.net/projects/chil360-android/files/evo-ten/osprey/EvolutionX_4.4_osprey-10.0-20200629-1058-UNOFFICIAL.zip/download)

First build of Evolution X 10.0 for Osprey. This rom has built-in GApps (with the same packages as my PE build).

<hr>

### POSP Croquette v3.2.0-hotfix+16

Download: [potato_osprey-10-20200620-croquette.v3.2.0-hotfix+16.Community.zip](https://sourceforge.net/projects/chil360-android/files/potato-ten/osprey/potato_osprey-10-20200620-croquette.v3.2.0-hotfix+16.Community.zip/download)

New build updating POSP sources to v3.2.0-hotfix+16 which fixes a few problems in last release. Also, fix a couple of device issues.

**Device changes:**
  - bootanimation: Use low res version of the POSP bootanimation for 1gb devices
  - screenrecord: Switch back to H264 encoding

<hr>

### POSP Croquette v3.2.0+15

Download: [potato_osprey-10-20200619-croquette.v3.2.0+15.Community.zip](https://sourceforge.net/projects/chil360-android/files/potato-ten/osprey/potato_osprey-10-20200619-croquette.v3.2.0+15.Community.zip/download)

First build of POSP Croquette for Osprey.

<hr>

### PixelExperience Plus 10.0

Download: [PixelExperience_Plus_osprey-10.0-20200614-1346-UNOFFICIAL.zip](https://sourceforge.net/projects/chil360-android/files/pixel-ten/osprey/PixelExperience_Plus_osprey-10.0-20200614-1346-UNOFFICIAL.zip/download)

First build of PixelExperience Plus 10.0 for Osprey. This rom has built-in GApps which I have modified to better support 32bit devices and to slim it down a little.

<hr>

### Announcement: Lineage OS 17.1 builds DISCONTINUED

As official builds of Lineage OS 17.1 for Osprey are now available, I will be discontinuing my unofficial builds. Monthly builds of my other Q roms will continue as normal.
I advise that anyone using my Lineage OS builds should switch to the official builds for ongoing updates.

**Official Lineage Downloads:** [https://download.lineageos.org/osprey](https://download.lineageos.org/osprey)

Note: Switching to the official Lineage OS builds will require a clean flash so remember to back up your data first.

<hr>

### Dirty Unicorns 14.4

Download: [du_osprey-v14.4-20200609-1026-UNOFFICIAL.zip](https://sourceforge.net/projects/chil360-android/files/du-14.x/osprey/du_osprey-v14.4-20200609-1026-UNOFFICIAL.zip/download)

Monthly build of Dirty Unicorns including the June security patches.

**Device changes:**

Kernel:
  - Backport scripts/dtc to allow compilation with GCC 10

Vendor:
  - Use RenderScript blobs from Channel QPY30.52-2
  - Update Time Services from Channel QPY30.52-2
  - Update Peripheral Manager from Channel QPY30.52-2
  - Update DRM Widevine from Channel QPY30.52-2

Device Tree
  - rootdir: Revert back to old FM init prop
  - overlays: Disable DiscoveryService
  - extract_firmware: Implement dynamic system mount
  - time-services: Create correct data dirs for time_daemon
  - Re-enable Peripheral Manager
  - sepolicy: Bump Widevine HAL to 1.2

<hr>

### Havoc OS 3.6

**Download:** [Havoc-OS-v3.6-20200608-osprey-Unofficial.zip](https://sourceforge.net/projects/chil360-android/files/havoc-3.x/osprey/Havoc-OS-v3.6-20200608-osprey-Unofficial.zip/download)

Monthly build of Havoc updated with the June security update.
 
**Device changes:**

Kernel:
  - Backport scripts/dtc to allow compilation with GCC 10

Vendor:
  - Use RenderScript blobs from Channel QPY30.52-2
  - Update Time Services from Channel QPY30.52-2
  - Update Peripheral Manager from Channel QPY30.52-2
  - Update DRM Widevine from Channel QPY30.52-2

Device Tree
  - rootdir: Revert back to old FM init prop
  - overlays: Disable DiscoveryService
  - extract_firmware: Implement dynamic system mount
  - time-services: Create correct data dirs for time_daemon
  - Re-enable Peripheral Manager
  - sepolicy: Bump Widevine HAL to 1.2
  - Updates for encryption

<hr>

### Lineage 17.1

**Download:** [lineage-17.1-20200607-UNOFFICIAL-osprey.zip](https://sourceforge.net/projects/chil360-android/files/lineage-17.1/osprey/lineage-17.1-20200607-UNOFFICIAL-osprey.zip/download)

Monthly build of Lineage OS including the June security patches.

**Device changes:**

Kernel:
  - Backport scripts/dtc to allow compilation with GCC 10

Vendor:
  - Use RenderScript blobs from Channel QPY30.52-2
  - Update Time Services from Channel QPY30.52-2
  - Update Peripheral Manager from Channel QPY30.52-2
  - Update DRM Widevine from Channel QPY30.52-2

Device Tree
  - extract_firmware: Implement dynamic system mount
  - time-services: Create correct data dirs for time_daemon
  - Re-enable Peripheral Manager
  - sepolicy: Bump Widevine HAL to 1.2
  - Updates for encryption

<hr>

### AOSiP 10.0 Quiche

**Download:** [AOSiP-10-Quiche-osprey-20200605.zip](https://sourceforge.net/projects/chil360-android/files/aosip-10.0/osprey/AOSiP-10-Quiche-osprey-20200605.zip/download)

Monthly build of AOSiP Quiche including the June security patches.

**Device changes:**

Kernel:
  - Backport scripts/dtc to allow compilation with GCC 10

Vendor:
  - Use RenderScript blobs from Channel QPY30.52-2
  - Update Time Services from Channel QPY30.52-2
  - Update Peripheral Manager from Channel QPY30.52-2
  - Update DRM Widevine from Channel QPY30.52-2

Device Tree
  - rootdir: Revert back to old FM init prop
  - overlays: Disable DiscoveryService
  - extract_firmware: Implement dynamic system mount
  - time-services: Create correct data dirs for time_daemon
  - Re-enable Peripheral Manager
  - sepolicy: Bump Widevine HAL to 1.2
  - Updates for encryption

<hr>

### ParanoidAndroid Quartz

**Download:** [pa-quartz-3-osprey-20200603-dev.zip](https://sourceforge.net/projects/chil360-android/files/pa-quartz/osprey/pa-quartz-3-osprey-20200603-dev.zip/download)

Monthly build of ParanoidAndroid Quartz including the June security patches.

**Device changes:**

Kernel:
  - Backport scripts/dtc to allow compilation with GCC 10

Vendor:
  - Use RenderScript blobs from Channel QPY30.52-2
  - Update Time Services from Channel QPY30.52-2
  - Update Peripheral Manager from Channel QPY30.52-2
  - Update DRM Widevine from Channel QPY30.52-2

Device Tree
  - rootdir: Revert back to old FM init prop
  - overlays: Disable DiscoveryService
  - extract_firmware: Implement dynamic system mount
  - time-services: Create correct data dirs for time_daemon
  - Re-enable Peripheral Manager
  - sepolicy: Bump Widevine HAL to 1.2
  - Updates for encryption
