# `!browse`

This alias allows you to browse through various data structures within Avrae. 

You can look at GVARs (and look through them if they are a properly formatted JSON), your characters `get_raw()`, and combatant information in the init tracker.

## How does it work?

The basics of how the alias works can be found by running `!browse ?` in Avrae. 

Once you have input your data type, you can browse through it by adding more args, which will be used as keys or indexes for the displayed dictionary or lists.

`!browse` on its own with no args will just display your `get_raw()`, so you can `!browse skills` and it will display your different skill bonuses.

[![Looking at Testy McTesterson's get_raw](https://cdn.discordapp.com/attachments/720465301329805332/733893503280742460/unknown.png)]

If you provide a GVAR ID as the first argument (`!gvar 5941c85d-4ebf-445d-8bdd-3df51fb7de9c`), it will attempt to load and display that GVAR. If its a JSON, it will load it as such and display it, allowing you to 'browse' inside of the data structure. Additional args will be used as keys/indexes (`!browse 5941c85d-4ebf-445d-8bdd-3df51fb7de9c T` will load the 'T' key in that JSON)

[![Looking at the 'T' key inside that GVAR JSON](https://cdn.discordapp.com/attachments/720465301329805332/733893769291628554/unknown.png)]

You can also look through combatants in init by using `!browse combat`, viewing various information on them. 

[![Looking at Korbin in combat](https://cdn.discordapp.com/attachments/720465301329805332/733893369293439006/unknown.png)]

## Credits

`@nadizak#5061` wrote the original `!browse` alias, but much later on `Derixleth#0636` and I rewrote it from the ground up using the tembed method, allowing us to expand usability and add a help command.