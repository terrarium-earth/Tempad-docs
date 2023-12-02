# Timer

The timer option is the default option for the normal Tempad. Setting the fuel option for the tempad to be **`tempad:timer`**
will make the Tempad use the timer fuel option. 

The timer option adds a **cooldown** to the Tempad. This cooldown is the amount of time in seconds that the Tempad will be
unable to be used after it has been used. The default cooldown is 180 seconds, or 3 minutes. This cooldown can be
configured by changing the **fuel amount** for the respective tempad. Fuel capacity is ignored.

## Definitions

> Note! The **fuel capacity** option is not used for the timer option, so you can set it to whatever you want and it will not affect
> the Tempad.

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the timer option is **`tempad:timer`**.

### Fuel amount

The fuel amount is the amount of fuel the Tempad uses. The fuel amount for the timer option is the amount of **time in
seconds** that the Tempad will be unable to be used after it has been used. The default fuel amount is 180 seconds, or 3
minutes.

## Example use cases

### Normal tempad
```json
{
    "timedoorFuelType": "tempad:timer",
    "timedoorFuelAmount": 180
}
```

### Advanced tempad
```json
{
    "advancedTimedoorFuelType": "tempad:timer",
    "advancedTimedoorFuelAmount": 180
}
```
