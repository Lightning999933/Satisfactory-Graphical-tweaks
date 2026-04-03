mod features: Lumen GI/reflection improvements, Virtual shadow maps support, FSR SSR bug fix, presets for quick and easy installation, research file with all my findings

discord server: https://discord.gg/gTSK8y9Tyd (for troubleshooting, suggestions, changelogs, pretty much anything)

This is currently an experimental build, theres only limited testing at this time, performance impacts of some presets arent clear, and the presets require more refinment
rendering resolution also effects the render distance of VSM's and the quolity of other rendering effects such as lumen so take that into account 

about installation
once you extract the files within the zip, you will find 3 folders, and 3 documentation files
the shadow presets effect the games shadow aspect, whereas the general presets effect lighting, reflections, etc (and the "perfectionist" is a combination of the 2)
within each folder you will find a txt file called "installation notes.txt" read that before installing

recommended in game settings:
for the shadow presets to work you must set the in game shadow quality to ultra
however on the experimental branch you also have to enter the command r.Shadow.Virtual.Enable 1 if you want to enable the tweaks 
however note that in experimental its not recomended as structure shadows are only drawn like 10 meters from the player, which looks terrible around factories, works fine in forests and such though

i also recommends setting lumen to the high setting in game
as well as that i also recommend selecting DLSS/FSR as upscaling (FSR for AMD/GTX GPU owners, DLSS for RTX GPU owners)
you can do whatever you want with the rest of the settings
