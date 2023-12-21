Create Hit Dice counters, and allows you to set your subclass, following the existing naming format as set by the popular but no longer updated `!level` alias.

`!classinfo [class] [subclass]`

Can be updated to add new classes and subclasses, change when a class get subclasses and what size of hit dice they get. You can use the following format in a `class_info` svar or uvar. `hit_die` and `sub_level` will _replace_ the existing value, and `subclasses` will _append_ to the current list.

```json
{
  "Barbarian":{
    "hit_die": 20,
    "sub_level": 1,
    "subclasses": [
        "Poppa Johns"
    ]
  }
}
```



[Base GVAR](https://avrae.io/dashboard/gvars?lookup=a53f12b4-bd1d-40d7-844f-9403a7dc5246) | [Github](https://github.com/Croebh/Avrae-Customizations/tree/master/Collections/Croebh's%20Class%20Info)