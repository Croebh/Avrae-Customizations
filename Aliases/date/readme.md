# `!date` and `!curdate`

These aliases allow you to view and set dates o different calendars. You can create custom calendars for use in your homebrew settings. It has support for months, days between months, seasons, holidays, and moon cycles (and several moons)

`!curdate` is a trimmed down version of `!date`, and uses `time()` and some simple math to find todays actual date/time and display it.

## How does it work?

You can find help in Avrae by running `!date ?`. You can find more specific help for creating custom calendars by running `!date custom`

`!date` on its own will look at the currently set date, whereas `!date #` lets you look at specific dates. You can advance/rewind the current date with `!date next` or `!date prev`, or set the date with `!date set #`.

[![Setting the date](https://cdn.discordapp.com/attachments/677592300313903105/733900003394715738/unknown.png)]

You can change the calendar by making a cvar/uvar named `DateGvar` containing the calendar GVAR you'd like to use.

For `!curdate`, you can set your timezone offset by making a uvar named `timezone` with your offset.

[![!curdate with my offset for MST](https://cdn.discordapp.com/attachments/677592300313903105/733900314444431430/unknown.png)]