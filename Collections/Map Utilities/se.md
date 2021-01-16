__**Map Utility**__
This is a utility to use with the `!map` alias. It allows you can quickly place preset spell effect overlays or ones that you have saved.
 
__**Basic Commands**__
`!se <name of spell/saved overlay> [aim] [-t <target>] [-n]` - You can place a preset spell effect overlays or one you have saved. If the name contains multiple words, you need to have it in quotes. It will auto attach the overlay to your active character or current character in initiative. If there is an {aim} in the spell preset, then you can input either a combatant name or location. Example: `!se "Circle of Death" b9` or `!se burning go1`

If you want to attach the overlay to another combatant than your active character or current character in combat, you can add `-t <combatant name>` at the end of all arguments. Example: `!se colorspray prixaris -t go1`

All overlays will automatically stick and remain if the `!map` alias is called unless `-n` is placed as the last argument. Example: `!se fireball d5 -n`
 
__**Other Commands**__
`!se -aim <target/location>` - This will change the aim of the overlay of your current active character or current character in initiative.
`!se none` - Remove the attached overlay to your active character or current character in initiative.
`!se list` - See a list of all ready-made spell overlays.