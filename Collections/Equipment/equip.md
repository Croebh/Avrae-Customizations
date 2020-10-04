 `!equip [weapon]` - Adds an attack with the named weapon. Has support for all PHB basic weaponry.

__**Valid Arguments: Basics**__
`-b <to hit bonus>` - adds a bonus to hit 
`-d <damage bonus>` - adds a bonus to damage
`-name <custom name>` - gives the weapon a custom name. Use \"quotes\" for multi-word names (for example: \"Frost Brand Shortsword\")
`-stat <str/dex/con/int/wis/con>` - uses a different ability score for the attack and damage roll 
`-t <target>` - adds an attack to a target in initiative. Automatically assumes +0 for attack and damage rolls, and must be manually adjusted with `-b` and `-d`
`magical` - makes the weapon magical
`adamantine` - makes the weapon adamantine
`silvered` - makes the weapon silvered
`monk` - exchanges the weapon's damage dice for Martial Arts dice (use only for monk weapons)
`2h` - only for versatile weapons: marks the attack as using two-hands
`off` - marks the weapon as offhand for two-weapon fighting, and removes bonus damage from Strength or Dexterity modifier
`savage` - sets the weapon to roll damage dice twice and choose the higher as per the Savage Attacker feat (use only for melee weapons)

__**Valid Arguments: Fighting Styles**__
`archery` - applies the Archery Fighting Style (use only for ranged weapons)
`dueling` - applies the Dueling Fighting Style (use only for non-two-handed weapons)
`gwf` - applies the Great Weapon Fighting Style (use only for two-handed weapons, or alongside `2h` for versatile weapons)