# `!map` and `!move`

These two aliases allow you utilize the wonder of [On The Fly Battle Maps](https://github.com/digitalsadhu/otf-battlemaps) inside of [Avrae](https://github.com/avrae/avrae). It uses notes insides of Avrae's initiative tracker in order to store combatant locations. 

Using the aliases, you can view the map, move combatants around, and display overlays for things such as spell effects or class abilities.

## How does it work?

Help for both aliases can be found by running `!map ?`, with more specific overlay help found with `!map ? overlay`

The gist of it is that you can move combatants around with `!map -t <target> -move <location>`. You can also set their size (`-size`) and color (`-color`) at the same or other times. An important note is that Large+ sized combatants are placed by the top left coordinate.

[![Moving someone, while changing their size and color](https://cdn.discordapp.com/attachments/720465301329805332/733890596191731792/unknown.png)]

You can also place overlays on the map, using the `-over` command. Theres support for circles, cones, lines, arrows, and squares. You can aim these at specific coordinates or even combatants (`{aim}` and `-aim`), as well as attaching them to combatants, either just for persistence, or for their coordinates for things like a paladin aura.

[![Placing a circle overlay, one of several types available](https://cdn.discordapp.com/attachments/720465301329805332/733890802270601267/unknown.png)]

`!move` is a simple shortcut for `!map -t <name> -move`, so doing `!move B3` would move your currently active character to B3. The alias uses the argparse .last() method, so you can override the target with another `-t` (`!move B3 -t or1` for instance).

[![Basic use of !move](https://cdn.discordapp.com/attachments/720465301329805332/733889999816359946/unknown.png)]

## Credits

Big thank you to `@Nerds and Dragons#2817` on the OTFBM dev server, who put together the default spell list gvar. Solid work, thanks!