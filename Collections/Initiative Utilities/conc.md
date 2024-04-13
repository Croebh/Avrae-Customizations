Rolls concentration saves for a caster. Will remove any concentration effects on a failure.

`!conc` - Rolls a concentration save with DC 10.

__Valid Arguments__
`-t [target]` - Selects a target for the check
`-dc [dc]` - Sets the DC (Damage divided by 2, min 10).
`adv`/`dis` - Rolls at advantage/disadantage. The alias checks for the 'War Caster' feat in a `feats` cvar, and for "Eldritch Mind" invocations in a `invocations` cvar (created manually, or set by the `!manage` alias).
`-b [conditional bonus]` - Adds (or subtracts) a bonus to the saves (accepts dice).
`-mc [minimum diceroll]` - Allows you to set a minimum roll on the save for features like Stars Druid: Dragon
`bs` - Adds your Intelligence modifier for when Bladesong is active. The alias also checks for any active effects in init that grant save bonuses.
`ts` - Adds your Proficiency bonus for when you're holding a Transmuter's stone that grants proficiency in Constitution Saves. The alias also checks for an effect called "Tranmuter's Stone" to apply the bonus. 
`-reroll [#]` - Sets a reroll amount for the save.
`-rr [#]` - Allows you to roll multiple saves at once
