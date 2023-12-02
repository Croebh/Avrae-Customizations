This alias handles making out of combat saving throws with all published Summon Spells, Companion Subclasses, and Homunculus Servant. 

To use: `ssave <summon or save> [save] [-with ability] [other args]`
 
The first argument can either be the name of a summon or the name of a save. 
If it is the name of a save, it will use the summon you used previously. If the first argument is the name of a summon, it will set the summon to that and then roll the save according to the second argument. 
  
**Additional Arguments**
Supports the same arguments that `!check` does.
  
**Limitations**
This alias cannot ask for input if you match multiple different save, so be sure to be specific enough. Also, make sure you do not have a homebrew monster named Commoner, as this alias leverages this default statblock to function.
  
**Spells and Companions**
`aberration, beast, blighted, celestial, construct, draconic, elemental, fey, demon, primal, reaper, shadowspawn, undead`
 
`dancing, drake, homunculus, land, sea, sky, steel, wildfire` 
For Primal Companion, specify the type (land, sea, sky)
