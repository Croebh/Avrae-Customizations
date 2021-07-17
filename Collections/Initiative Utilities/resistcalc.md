Deals damage that accounts for resistances of a target in combat.
`!resistcalc <dice> [args]` - dice is damage dice to apply to all targets

**__Valid Arguments__**
`-t <name>` - adds a target for the damage, accepts groups. If not targets are given it will use the current combatant
`-t "<name>|<args>"` - allows for target specific args
`-source <name>` - adds a source for the damage. Matches to a combatant or use the text as-is if not found
`crit` - deal critical damage
`-crit dice <num>` - bonus dice to add to each dice group on critical
`-c "<dice>"` - bonus damage to deal on critical
`-d "<dice>"` - extra dice to add, most useful for applying to specific targets
`-resist <type>` - Gives the combatant resistance to the given damage type.
`-immune <type>` - Gives the combatant immunity to the given damage type.
`-vuln <type>` - Gives the combatant vulnerability to the given damage type.
`-neutral <type>` - Removes the combatants' immunity, resistance, or vulnerability to the given damage type.
`overheal` - allows negative damage to heal past a target's max hp