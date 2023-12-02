# Experience points

Setting the fuel option for the tempad to be **`tempad:experience_points`** will make the Tempad use the experience points
fuel option.

The experience points option makes the Tempad consume experience points from the player's experience bar upon opening a time door,
which is set by the fuel amount. Fuel capacity is ignored.

## Definitions

> Note! The **fuel capacity** option is not used for the experience points option, so you can set it to whatever you want and it will not affect
> the Tempad.

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the experience points option is **`tempad:experience_points`**.

### Fuel amount

The fuel amount is the amount of fuel the Tempad uses. The fuel amount for the experience points option is the amount of
**experience points** the Tempad will consume from the player's experience bar.

## Example use cases

### Normal tempad
```json
{
    "timedoorFuelType": "tempad:experience_points",
    "timedoorFuelAmount": 15
}
```

### Advanced tempad
```json
{
    "advancedTimedoorFuelType": "tempad:experience_points",
    "advancedTimedoorFuelAmount": 15
}
```