# Levels of Experience

Setting the fuel option for the tempad to be **`tempad:experience_level`** will make the Tempad use the levels of experience
fuel option.

The levels of experience option makes the Tempad consume experience levels from the player's experience bar upon opening a time door, 
which is set by the fuel amount. Fuel capacity is ignored.

## Definitions

> Note! The **fuel capacity** option is not used for the levels of experience option, so you can set it to whatever you want and it will not affect
> the Tempad.

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the levels of experience option is **`tempad:experience_level`**.

### Fuel amount

The fuel amount is the amount of fuel the Tempad uses. The fuel amount for the levels of experience option is the amount of
**experience levels** the Tempad will consume from the player's experience bar.

## Example use cases

### Normal tempad
```json
{
    "timedoorFuelType": "tempad:experience_level",
    "timedoorFuelAmount": 2
}
```

### Advanced tempad
```json
{
    "advancedTimedoorFuelType": "tempad:experience_level",
    "advancedTimedoorFuelAmount": 2
}
```
