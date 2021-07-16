# Default dante presets for the ASIL, Maker space & Pluriversum labs
Default dante presets for the labs.  Several presets are provided. Channel naming provides details to the labs. LTC clock distribution is enabled by default (syncmaster) and should not be changed.


### Best practice for saving custom presets
When saving a dante preset; only select the relevant devices (hold CTRL to select multiple). In the advanced menu, click 'none' and then only select "RX channel subscriptions".  This will allow for faster preset loading.


## DANTE-IPEM_default
Last update june 2021
Starting point for new routings.  Any new setup should probably start from this one.

## DANTE-IPEM-Reset_all
Resets ALL IPEM devices to their default state.  This includes naming, ip adresses, latency, clock settings,   labels, etc.  Do not use unless there are networking issues.


## DANTE_Ambisonics_6th_62spk_RACKPC-binaural
Ableton live - Envelop for live ASIL presetup.  62 speakers ambisonics rendering, 2 speakers binaural (big desk headphones). 
Runs on rack pc.


## DANTE-Ambisonics-3thOrder-MachineroomPC-MS-Synthi
Ableton live - Envelop for live Maker space presetup.  8 speakers ambisonics rendering.
Runs on Machineroom pc.

## DANTE-Ambisonics-7thOrder-RackPc-To-MachineroomPC-to-Speakers
7th order ambisonics rendering using Max MSP and IEM VST's.
Encoding on Rack PC, decoding on Machineroom PC, playback in ASIL (80 speakers)

## DANTE-Ambisonics-7thOrder-RackPc-to-Speakers
7th order ambisonics rendering using Max MSP and IEM VST's.
Encoding and decoding on Rack PC (heavy on the CPU - whatch out for clicks), playback in ASIL (80 speakers)

## DANTE-IOSONO-FromRackPC2021
Default IOSONO Preset.  Runs on rack PC, rendering in ASIL (62 speakers).
