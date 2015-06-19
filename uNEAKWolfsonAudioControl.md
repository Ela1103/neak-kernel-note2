# Introduction #

What is Wolfson Audio Control?

AndiP, a great developer for the I9300, did a complete and clean rewrite of the whole voodoo/scoobydoo driver, which is named Boeffla Sound. The name change is just to fix better the different kernel approach (no changes at all in the code).

Everything you did with Voodoo/ScoobyDoo is now available in an easier interface with Wolfson Audio.

uNEAK Engine and BoefflaSound Control are the only apps capable of controlling this driver fully and easily. Also with some great additions.

# Details #

Options available into Wolfson Audio Control:

1) Advanced Settings

2) DAC Direct

3) DAC Oversampling

4) FLL Tuning

5) Speaker Tuning (PRO)

6) Stereo Expansion (PRO)

7) Mono Downmix (PRO)

8) Headphone Amplification

9) Speaker Amplification

10) General Mic Gain

11) Call Mic Gain

12) Hardware Equalizer Switch

13) Graphical Hardware Equalizer (with presets)

# Explanations #

**DAC Direct**
Bypasses the analong channel conversion, to have a full DAC experience and improve drastically audio quality and frequency range.

**DAC Oversampling**
By applying a 128x oversampling, the audio quality is heavily improved in quality and clarity.

**FLL Tuning**
Tunes the audio chip clock engine, to ensure the right power to your headphones and reduce distorsions and bad behaviours.

**Speaker Tuning**
Only available in PRO version of the app, tunes up the bands and gains of the phone speaker for a more powerful sound. May cause distorsion.

**Stereo Expansion**
Only available in PRO version of the app, tunes up the headphone output, increasing the music deepness and clarity, for a better and more clear sound, with less distorsions.

**Mono Downmix**
Only available in PRO version of the app, converts every stereo signal into a mono signal, so each stereo channel ears the same sounds.

**Headphone Amplification**
Pump up your headphones volume by raising this value (from 45 to 63). Be careful of your ears, and don't exceed too much with the volume. High volume levels may cause distorsions if your headphones aren't capable of such power.

**Speaker Amplification**
Raise your phone speaker volume to have louder output. This causes most of the times distorsions and loss of quality, due to the low power of the phone speaker.

**General Mic Gain**
Allows to modify the general volume of the microphone for every situation, except for calls. If reduces, it reduces also mic sensitivity, allowing to record sounds in loud environments.

**Call Mic Gain**
Same as previous, but applies only for calls.

**Hardware Equalizer**
Enable the hw equalizer to tune up manually the frequency bands and improve the sound quality. All depends up to you.

**Graphical Equalizer**
Use the sliders to raise the amplification of each frequency band, also 2 modes of working of the equalizer are provided (normal and over-saturation suppress). The 2nd one is reccomended for audio quality and power. Now there are also some equalizer presets that may suit for your needs, just select them from the app. Also if you enable the "Bass Tuning", the basses will be greatly improved when using high gains on low frequencies.

# Advanced Settings #

**Set On Boot**
Allows you to set the currently set values in the app on boot directly, without using any kind of scripts. Speaker amplification is excluded.

**Volume Buttons Mapping**
This is an exclusive and completely written from scratch feature (also seen in original Voodoo Plus app). If you enable it, the headphones hardware amplification level will be an "extension" of the usual software volume, all controllable with the volume buttons.

Behaviour:

- from 0 to 100% software volume behaves normally.

- if you raise the software volume over 100%, it raises the hardware volume until max hardware volume (1 step for each button press).

- if you're in the hardware volume range, and you lower it, you will lower the hardware volume until it reaches the lowest value (50), then it lowers the software volume as usual

**Show Gain Popup**
Only available in the PRO version, this exclusive and completely written from scratch feature, shows a small popup/window on the bottom of the screen every time you modify the headphones gain with the volume buttons hack. The popup goes away after 2 secs from the volume change, and it shows a slider and a text saying the volume gain.

**Jack Plug-In Safety**
When plugging in the headphones, the hardware amplification volume is set automatically to the lowest possible (45) to ensure a safe volume for your ears.

**Privacy Mode**
When using the headphones, it auto-mutes the speaker, so any kind of notification or sound will be played only in your headphones.