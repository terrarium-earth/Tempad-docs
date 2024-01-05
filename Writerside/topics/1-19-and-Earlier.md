# 1.19 and Earlier

By editing the `tempad.json`, you can change how the tempad and the timedoor work.

## Tempad Options

The biggest changeable option is what the tempad requires in order to open a timedoor.

To change the normal tempad, change the `timedoorUsageType` field. The values for the tempad usage type are taken from the `configurationOptionsForTempad` object.

To change the 'he who remains' tempad, change the `kangTimedoorUsageType` field. The values for the tempad usage type are taken from the `configurationOptionsForHeWhoRemainsTempad` object.

The following are all the possible usage types

### `"ENERGY"`

This option will make the Tempad now hold FE or TechReborn energy. The amount of energy it holds is dictated by `timedoor_energy_capacity_if_usage_type_is_set_to_ENERGY` and the amount it consumes per timedoor open (when not in creative) is `timedoor_energy_cost_if_usage_type_is_set_to_ENERGY`

### `"DURABILITY"`

This option will make the Tempad have a limited amount of uses before it breaks. The amount of durability isn't configurable. The normal Tempad has 100 uses, while the 'He who remains' Tempad has 1000 uses.

### `"ITEM"`

This option will make the Tempad require an item in your inventory in order to summon a timedoor. The item that can be used is dictated by an item tag called `tempad:tempad_fuel`. You can add to this tag or override it to change the fuel items.

### `"TIMER"`

This option will put the Tempad on cooldown after it summons a timedoor. The amount of time it needs to recharge is dictated by the `timedoor_cooldown_if_usage_type_is_set_to_TIMER` field in the config.

### `"EXP_POINTS"`

This option will make the Tempad require experience points in order to summon a timedoor. The amount of experience needed is dictated by the `timedoor_experience_cost_if_usage_type_is_set_to_EXP_POINTS`.

### `"EXP_LEVELS"`

This option will make the Tempad require experience levels in order to summon a timedoor. The amount of experience needed is dictated by the `timedoor_experience_level_cost_if_usage_type_is_set_to_EXP_LEVELS`.

### `"UNLIMITED"`

This option will make the Tempad require no fuel or limit of any kind when trying to summon a timedoor.
