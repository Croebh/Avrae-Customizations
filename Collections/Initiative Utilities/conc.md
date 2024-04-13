Rolls concentration saves for a caster. Will remove any concentration effects on a failure.

`!conc` - Rolls a concentration save with DC 10.

__Valid Arguments__
`-t [target]` - Selects a target for the check
`-dc [dc]` - Sets the DC (Damage divided by 2, min 10).
`adv`/`dis` - Rolls at advantage/disadantage. The alias checks for the 'War Caster' feat in a `feats` cvar, and for "Eldritch Mind" invocations in a `invocations` cvar (created manually, or set by the `!manage` alias).
`-b [conditional bonus]` - Adds (or subtracts) a bonus to the saves (accepts dice).
`-mc [minimum diceroll]` - Allows you to set a minimum roll on the save
`-reroll [#]` - Sets a reroll amount for the save.
`-rr [#]` - Allows you to roll multiple saves at once

`bs` - Adds your Intelligence modifier for when Bladesong is active. The alias also checks for an active effect named "Bladesong" to apply the bonus.
`ts` - Adds your Proficiency bonus for when you're holding a Transmuter's stone that grants proficiency in Constitution Saves. The alias also checks for an effect called "Tranmuter's Stone" to apply the bonus. 
`dragon` - Sets the Minimum Check to be 10 for when Starry Form: Dragon is active. The alias also checks for an active effect named "Starry Form" with a description starting with "Constellation: Dragon" to apply the bonus.