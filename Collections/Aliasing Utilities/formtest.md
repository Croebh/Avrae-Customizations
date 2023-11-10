This alias is for checking the math of level based formulas. Use `level` in the formula where it would go, like `!formtest 1+floor((level+1)//6)` is cantrip scaling while `!formtest floor((level+7)/4)` is proficiency bonus scaling.
 
**Cantrip:** `1+floor((level+1)/6)`
**Proficiency Bonus:** `floor((level+7)/4)`
**Bardic Inspiration:** `6+2*((level>=5)+(level>=10)+(level>=15))`
**Psionic Die:** `6+2*((level+1)//6)`
**Martial Arts/Hemocraft:** `4+2*((level+1)//6)`
**Sneak Attack:** `(level+1)//2`
**Warlock Slot:** `min(5, ceil(level/2))`