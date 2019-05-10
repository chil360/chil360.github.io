### Dirty Unicorns 13.2 - Monthly Build

**Download:** [du_osprey-v13.2-20190510-1325-UNOFFICIAL.zip](https://www.androidfilehost.com/?fid=1395089523397963054)

**Changes:**
 - Kill pinner service: Don't hold core system components in memory as it consumes too much RAM (especially for 1Gb devices) with little performance benefit.

**Note:** DU builds will be monthly from now on as there has been very few changes to the rom source recently.

<hr>

### Dirty Unicorns 13.1 - Weekly Build

**Download:** [du_osprey-v13.1-20190426-1152-UNOFFICIAL.zip](https://www.androidfilehost.com/?fid=1395089523397953532)

**Changes:**
- Kernel built with updated GCC 8.3-2019.03 toolchain
- Kernel changes: backported binder updates, add core_ctl, some additional cpufreq commits
- Power config: configure cpusets, interactive govenor tweaks (core_ctl is disabled as was found to be too aggressive)
- Audio: Use deep_buffer instead of low_latency - this, hopefully, now fixes the audio crackling issue.
- Audio: Uprev Audio HALs to 4.0
- Actions: Integrate MotoActions into DU-Tweaks under 'Device Extras'

<hr>

### Dirty Unicorns 13.1 - Test Build

**Download:** [du_osprey-v13.1-20190412-1825-UNOFFICIAL.zip](https://www.androidfilehost.com/?fid=1395089523397944555)

New build to test out a few things...

**Changes:**
- Kernel built with updated GCC 8.3-2019.03 toolchain
- Kernel changes: backported binder updates, add core_ctl, some additional cpufreq commits
- Audio: Revert XML audio policy commits
- Power config: enable core_ctl, configure cpusets, interactive govenor tweaks

Please test general stablily after kernel & toolchain updates, check for audio crackling issue & test for any improvement in battery life.

<hr>

### RevengeOS 2.3 Pasta - Test Build 2

**Download:** [RevengeOS-2.3-Pasta-UNOFFICIAL-osprey-20190415-1957.zip](https://www.androidfilehost.com/?fid=1395089523397944194)

**Test Build 2 changes:**
- Add lag fixes
- SEpolicy fixes
- Built without GApps to better evaluate the stability the ROM

**Note:** Clean flash is required.

<hr>

### RevengeOS 2.3 Pasta - Test Build 1

**Download:** [RevengeOS-2.3-Pasta-UNOFFICIAL-osprey-20190414-1145.zip](https://www.androidfilehost.com/?fid=1395089523397943036)

This is a test build of RevengeOS which is a new CAF based rom that seems quite promising.

Note: GAPPS IS INCLUDED in the rom.

Try it out and see what you think. If people like it, I will try and make regular builds.

<hr>

### Dirty Unicorns 13.1 - Weekly Build

**Download:** [du_osprey-v13.1-20190412-1825-UNOFFICIAL.zip](https://www.androidfilehost.com/?fid=1395089523397940581)

Dirty Unicorns 13.1 weekly update

**Rom Changelog:** See [Gerrit](https://gerrit.dirtyunicorns.com/#/q/status:merged)

**Device Changelog:**
 - No device specific changes.

<hr>

### Lineage 16.0 - Monthly Build

**Download:** [lineage-16.0-20190407-UNOFFICIAL-osprey.zip](https://www.androidfilehost.com/?fid=1395089523397935875)

Lineage 16 monthly build with April security update

**Device changes since last month's build:**
- Sepolicy updates
- Manual network selection fixes (credits [https://github.com/nicorg2515](https://github.com/nicorg2515))

<hr>

### AICP 14.0 - Monthly Build

**Download:** [aicp_osprey_p-14.0-UNOFFICIAL-20190407.zip](https://www.androidfilehost.com/?fid=1395089523397935468)

AICP 14 monthly build with April security update

**Device changes since last month's build:**
- Sepolicy updates
- Manual network selection fixes (credits [https://github.com/nicorg2515](https://github.com/nicorg2515))

<hr>

### GZOSP 9 Beta 2.0 - Monthly Build

**Download:** [Gzosp-osprey-9.Beta.2.0-UNOFFICIAL-20190406-1257.zip](https://www.androidfilehost.com/?fid=1395089523397934522)

GZOSP monthly build with April security update.

<hr>

### Dirty Unicorns 13.1 - Weekly Build

**Download:** [du_osprey-v13.1-20190405-1732-UNOFFICIAL.zip](https://www.androidfilehost.com/?fid=1395089523397933958)

Dirty Unicorns 13.1 with April security update

**Rom Changelog:** See [https://dirtyunicorns.com/2019/04/05/official-13-1/](https://dirtyunicorns.com/2019/04/05/official-13-1/)

**Device Changelog:**
 - Manual network selection fixes (credits nicorg2515)
