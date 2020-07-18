# `!map` and `!move`

These two aliases allow you utilize the wonder of [On The Fly Battle Maps](https://github.com/digitalsadhu/otf-battlemaps) inside of [Avrae](https://github.com/avrae/avrae). It uses notes insides of Avrae's initiative tracker in order to store combatant locations. 

Using the aliases, you can view the map, move combatants around, and display overlays for things such as spell effects or class abilities.

## How does it work?

Help for both aliases can be found by running `!map ?`, with more specific overlay help found with `!map ? overlay`

`!move` is a simple shortcut for `!map -t <name> -move`, so doing `!move B3` would move your currently active character to B3. The alias uses the argparse .last() method, so you can override the target with another `-t` (`!move B3 -t or1` for instance).