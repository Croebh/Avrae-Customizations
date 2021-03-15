__**Map Utility**__
This is a utility to use with the !map alias. You can focus on a portion of a map as well as shift that view, expand it, or reduce it. You also have the option to save a view, so later on you can load it quickly.

__**View Commands**__
`!view <coordinate>:<coordinate>` - Focuses on a portion of the map. Example: `!view A3:K12`
`!view <coordinate>:<gridsize>` - Focuses on a portion of the map, but with a specified size instead of an end location. Example: `!view A3:4x10`
`!view reset` - Returns to full view.
`!view <distance and direction> shift` - Will shift the current view coordinates in whatever distance and direction given. Example: `!view 15e shift` would shift the view focus 15ft eastward. You can do multiple directions and distances `!view 15e10s shift`
`!view <distance and direction> expand` - Will expand the set view focus in whatever distance and direction given. Example: `!view 10n10e` expand would take a view focus of `c5:5x5` to `c3:7x7`
`!view <distance and direction> reduce` - Will reduce the current view focus in whatever distance and direction given. Example: `!view 10s10e` reduce would take a view focus of `f3:7x7` to `f3:5x5`
Direction can be n, ne, e, se, s, sw, w, nw

__**Saving, Loading and Deleting View Presets**__
`list` - Lists all saved view presets.
`-save <name>,<coordinate>:<coordinate>` - Saves a view preset. Example: `-save Ambush,K5:Z15`
`-load <name>` - Loads a saved view preset.
`-delete <name>` - Deletes a saved view preset.

**Issues?**
You can file reports and feature requests at OTFBM [GitHub](https://github.com/otfbm/issues)