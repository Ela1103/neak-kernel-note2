# Introduction #

uNEAK Engine is a simple but cool and full of features app, written and coded by simone201, expecially made for N.E.A.K. Kernel users, to configure the whole system easily and quickly.
It is released under Apache license, so it is not open source.
For now it supports S3 and Note2 JB kernels.

# Details #

**1) NEAK Smart Response**

With that feature, original and exclusive of uNEAK Engine, the user can easily set up the phone beaviour with just one click on the screen.
It allows 3 modes of working: Normal (default), Battery and Game.
- Normal mode means standard behaviour for both ROM and Kernel, which is set by default.
- Battery mode helps with saving some juice when needed, by reducing cpu frequencies, tuning pegasusq parameters, and setting the brightness to the lowest value. Also it sets the TouchBooster to a lower frequency. Of course the performances will be reduced after the use of that mode.
- Game mode is designed for heavy gamers, which need amazing smoothness on intensive games. It improves CPU scaling and TouchBooster responsiveness to ensure proper cpu power during games. It doesn't modify at all the GPU behaviour, as the user can do that by itself easily.

**2) NEAK Options**

These are the basic NEAK Kernel options, inherited from the S2 and S3 kernel. You can easily enable Conservative Gov module, tweak it, and enable Lazy Gov module.
Other options are SCHED\_MC (multicore), which improves core management for power consumption; AFTR+LPA Idle Mode improves battery savings by hitting the AFTR idle mode during low power tasks in regular working of the phone; EXT4 Boost tweaks the ext4 flags to improve NAND responsiveness and IO performances (it doesn't affect battery).

**3) CPU Control (ONLY PRO VERSION)**
Same as does Voltage Control or any other app, settings for frequencies, governors and schedulers, just included into the amazing uNEAK Environment. Needs the PRO KEY app to unlock this feature.

**4) CPU Voltage Control**

With this feature you can easily Undervolt (UV) your CPU by using easy sliders and set the values to be used on phone boot.
Be sure that your values are stable if you set them on boot.

**5) GPU Control**

As with the CPU, here you can control the GPU Clocks (OC) and Voltages (UV) by easy and simple popups with sliders, which do allow the user to Overclock or Underclock your GPU to improve gaming or power savings. Also controlling the GPU voltages do improve stability at higher clocks, or improve battery life at lower clocks. Be sure to have stable voltages before setting them on boot.
The GPU steps do depend on the device itself.

**6) Current Control**

Here you can change the charge currents of your phone for every kind of charger do you need. Raising currents make the charging faster, but remember that the power source should also be capable of such current to actually charge at the desired value.

**7) FSync Control**

FSync can be toggled only until the next boot, because of security purposes. By disabling it the NAND IO performances will be improved greatly, resulting in faster memory accesses and management, that can be seen by running a few benchs. Also having disabled FSync makes data corruption more probable, that's the reason because on boot it is re-enabled by default. (Other kernels with amazing IO scores surely have fsync disabled, which means probable data corruption)

**8) Wolfson Audio Control**

Check the new wiki for it!! LINK: http://code.google.com/p/neak-kernel-note2/wiki/uNEAKWolfsonAudioControl

**9) OTA Updater**

Check the new wiki for it!! LINK: http://code.google.com/p/neak-kernel-note2/wiki/uNEAKOTA

MORE TO COME