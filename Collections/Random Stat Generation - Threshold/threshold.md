Allows for rolling character stats while imposing a set of rules on the outcome.

**__Valid Arguments__**

`-dice <dice>` - The dice to be rolled for each stat. Default: `4d6kh3`
`-rr <#>` - The number of sets to be displayed. Default: 1
`-tries <#>` - The number of attempts it will try to find sets matching the rules.
`straight` - Will assign stats to each score.

`-min <#>` - The minimum total of the combined rolls.
`-max <#>` - The maximum total of the combined rolls.

`-over <#|amount>` - Requires `amount` of rolls that are above `#`. Can be repeated 
`-under <#|amount>` - Requires `amount` of rolls that are below `#`. Can be repeated.

Servers can set a default set of args by setting an svar named `threshold`:
Example: `!svar threshold -min 70 -over 14|1 -under 11|1`

**Support Us**
You can support me and this alias at [Ko-Fi](https://ko-fi.com/croebh)

**Issues?**
You can file reports and feature requests, as well as see the source code, at my [GitHub](https://github.com/Croebh/Avrae-Customizations)