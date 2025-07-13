mod features: Lumen GI/reflection improvements, Virtual shadow maps support, FSR SSR bug fix, 6 presets, research file with all my findings

discord server: https://discord.gg/UHxdAAYT (for troubleshooting, suggestions, changelogs, pretty much anything)

notes:
NOTE: This is currently an experimental build, theres next to no testing at this time, performance impacts of some presets arent clear, and the presets require more refinment

installation:
copy the engine.ini(and Scalability.ini) here %localAppdata%\FactoryGame\saved\config\Windows and overwrite the vanilla files with the same names

recommended in game settings:
for VSM's to work you must set the in game shadow quality to ultra
i also recommends setting lumen to the high setting in game
as well as that i also recommend selecting DLSS/FSR as upscaling (FSR for AMD/GTX GPU owners, DLSS for RTX GPU owners)
you can do whatever you want with the rest of the settings



changelog:
Update v0.5.1 Experimental
changelog:
changed r.Shadow.RadiusThreshold value in standard + VSM preset from 0.2 to 0.1, changed its value in high, medium + VSM preset from 0.2 to 0.07
deprecated the extreme preset 
changed r.Shadow.Virtual.ResolutionLodBiasDirectional,moving values from 0,8 to 0.9 in the standard preset, and changed it to 0,9 and 1 in the medium preset
changed r.Shadow.Virtual.Clipmap.LastLevel value from 15 to 16 in the high preset
