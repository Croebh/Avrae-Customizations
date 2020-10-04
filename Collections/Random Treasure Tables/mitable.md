Allows you to roll on the random magic item tables as laid out in the DMG.

`!mitable [A-I] [#|dice]` - String things together like `!mitable A 4 D 1d4 I 2` to roll on multiple tables at once. 
If you don't specify a number or dice the alias assumes 1 item, e.g. `!mitable a b c` rolls 1 item from each table. 

You can also set defaults so it will automatically roll on preset tables when you call !mitable with no arguments.
To do so, simply run `!svar mitableDefault PRESETS HERE`
Format them in a list, e.g. `!svar mitableDefault ["a","2","b","1d4","d","f"]` rolls 2 items on A, 1d4 on B, and 1 each on D and F.

**Support Us**
You can support me and this alias at [Ko-Fi](https://ko-fi.com/croebh)

**Issues?**
You can file reports and feature requests, as well as see the source code, at my [GitHub](https://github.com/Croebh/Avrae-Customizations)