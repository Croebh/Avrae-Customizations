This collection provides a variety of snippets to expend ammunition, as well as the `!collect` alias to retrieve your ammunition after a fight.
If you want to track the ammo fired create an svar|cvar|uvar named `trackShots` (EX: `!cvar trackShots 1`)

If you would like to create additional snippets for other types of ammunition, you can create a snippet like such:

```py
!snippet ammoNameHere {{c = 'AMMONAMEHERE'}}
{{C, F, ammoNameHereF, track = 'Used ' + c, 'Fired ' + c, get('ammoNameHereF', 0) + 1, get_svar('trackShots') or get('trackShots')}}
{{character().create_cc_nx(C, 0)}}
{{character().create_cc_nx(F, 0) if track else ''}}
{{(character().create_cc_nx(c, 0), character().set_cc(c, 20)) if not character().cc_exists(c) else ''}}
{{v = character().get_cc(c) > 0}}
{{miss = get('miss', 0) + (not v)}}
{{(character().mod_cc(c, -1), character().mod_cc(C, 1)) if v else f'miss{miss}'}}
{{character().mod_cc(F, 1) if v and track else ''}}
{{f'-phrase "{"Using a piece of AMMONAMEHERE" if ammoNameHereF == 1 else "...and another one"} ({character().get_cc(c)} remaining)"'}}
{{'' if ammoNameHereF > 1 else '-f "Ammunition|You can use a weapon that has the ammunition property to make a ranged attack only if you have ammunition to fire from the weapon. (PHB 146)"'}}
```

Make sure to replace `AMMONAMEHERE` and `ammonameHereF` with your ammo's name, as well as the name of the snippet.

**Support Us**
You can support me and this collection at [Ko-Fi](https://ko-fi.com/croebh)

**Issues?**
You can file reports and feature requests, as well as see the source code, at my [GitHub](https://github.com/Croebh/Avrae-Customizations)