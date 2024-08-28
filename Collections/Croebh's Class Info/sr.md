`!sr` performs a Short Rest resetting counters that reset on a short rest, regaining spell slots for warlocks, and spending Hit Dice if told to. 
 
**Valid Arguments:**
`XdY` - Spends X dY Hit Dice, e.g. `!sr 3d8` will spend 3 d8 Hit Dice to heal you. Now supports multiple die types at once, so you can do `!sr 1d12 2d10` to roll 1 d12 and 2 d10 Hit Dice for healing.
You can also just do `!sr X` to use X Hit Dice, starting with the largest available to you. If you want to set a default primary Hit Die size to use first that isn't your largest available, create a cvar named `defaultHD` and set it to a die type, e.g. `!cvar defaultHD d8`.
`-b XdY` - Adds extra dice to your healing roll without using Hit Dice, typically for use when you are resting with a bard and are affected by their Song of Rest, e.g. `!sr 3d8 -b 1d6` will spend 3 d8 Hit Dice and add a bonus d6 to your healing roll.
`max` - Rolls the maximum value for each Hit Die rolled. Does not apply to bonus healing.'''+f' 
 
**Automatically Accounted For Options**
**Durable Feat:** If you have the Durable feat, create a cvar named `feats` and put `Durable` in it. You can also just use the `dur` or `durable` argument with the alias to apply the effect.

**Bard: Song of Rest:** When you have levels in bard, this alias will automatically apply your personal Song of Rest bonus healing when you spend Hit Dice on a short rest (but not when you spend additional Hit Dice with `!rest extra`, also note that your party members still need to use `-b` as above).

**Periapt of Wound Closure:** If you have a Periapt of Wound Closure, create a cvar named `attunedItems` and put `Periapt of Wound Closure` in it. You can also use the `periapt` or `closure` argument with the alias to apply the effect. 

**Verdan: Black Blood Healing:** If your race is set as Verdan, `!sr` will automatically reroll any 1s or 2s you roll on a Hit Die.

`!sr` will try to automatically detect if you're a Warlock and recover pact slots appropriately. You can override this with `!cvar ignorePactSlots 1` to always disable recovering spell slots on short rest, or use `!csettings` -> Gameplay Settings -> Toggle Short Rest Slots to always recover *all* slots on short rest.
