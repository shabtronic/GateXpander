# GateXpander
Audio compressor, expander with noise gate functionality, it's only really good for distorted guitar (since my code currently distorts too much for clean sounds).

if Ratio is > 0 the Expander algorithm kicks in.

if Ratio is <0 the Compressor algorithm kicks in.

Here are some settings for a great noise gate for High gain guitar!

Reaper JS version:

![](./Images/GateExpander.png)


VST3 Version:

written using the excellent Iplug2 framework  (https://github.com/iPlug2/iPlug2)

This version has a seperate compress level - this mirrors when the knee level is above 0%.
it mirrors around the threshold value - so if the signal is above that value - it will pull the signal below the threshold level
by the same amount  - this gives that class "suckback" sound.

For guitar this means the harder you hit the strings the more the sound will fade in - this is great for slow power chord control.

Currently the VST3 presets are broken for some unknown reason.

![](./Images/GateExpanderVst3.png)
