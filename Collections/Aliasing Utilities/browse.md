This alias allows you to 'browse' `character()`, `get_raw()`, gvars, cvars, and combat.
Once you're in the mode you want, you can make a search through different levels of the selected object using space separated search terms. This alias has fuzzy-search-like behaviour.

**__Examples__**

`!browse skills acro` will bring you to `character().skills.acrobatics`, and display the value.
`!browse att 0 na` will bring you to `character().attacks[0].name`, and display the name of your first attack.
`!browse combat or1 ac` will bring you to `combat().get_combatant('or1').ac`, displaying the current ac of OR1.
`!browse ctx author disp` will show you `ctx.author.display_name`, displaying your nickname on that server.

**Note:** There are many things in both the SimpleCombatant and character() models that are *not* exactly as they appear in this alias. Specifically things like Resistances, where I have, in this alias, reconstructed them as dicts. The code in the title of the embed should still function to get the information.

**__Modes__**

`!browse [search]` - Browses your characters `character()`
`!browse get_raw` - Browses your characters `get_raw()`
`!browse <gvarid> [search]` - Browses that gvar, and loads it as a json if it is one
`!browse cvar <cvarname> [search]` - Browses that cvar, and loads it as a json if it is one
`!browse combat [search]` - Browses the channels `!init` by combatant.
`!browse <ctx|context> [search]` - Browses the `ctx` context model.

**Support Us**
You can support me and this alias at [Ko-Fi](https://ko-fi.com/croebh)

**Issues?**
You can file reports and feature requests, as well as see the source code, at my [GitHub](https://github.com/Croebh/Avrae-Customizations)