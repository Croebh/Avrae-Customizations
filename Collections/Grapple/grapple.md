`!grapple [args]`

**__Valid Arguments__**

`-c [grappler]` - The person making the grapple. Defaults to active character.
`-t [target]` - The target of the grapple
`acro` - Forces the targets check to be acrobatics

`-b #` - Adds a bonus to the grapple check
`adv`/`dis` - Rolls the check at dis/advantage
`-stat [stat]` - Use a different stat mod for the grappler
`-tstat [stat]` - Use a different stat mod for the target

You can do target specific, i.e, `-t OR1|dis` or `-c "GO1|-b 5"`

`shove` - Denotes that the grapple is an attempt to shove. Can be combined with `trip`
`trip` - Denotes that the grapple is an attempt to trip. Can be combined with `shove`

`-desc [description]` - Adds a description
`-title [title]` - Replaces the title. `[grappler]` and `[target]` get replaced with their respective names.
`-thumb [url]` - Adds a thumbnail
`-image [url]` - Adds an image at the bottom