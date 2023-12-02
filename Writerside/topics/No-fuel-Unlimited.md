# No fuel/Unlimited

The unlimited option is the default option for the advanced Tempad. Setting the fuel option for the tempad to be **`tempad:unlimited`**
will make the Tempad use the unlimited fuel option.

The unlimited option makes the Tempad not use any fuel. Both the fuel capacity and fuel amount are ignored.

## Definitions

> Note! The **fuel capacity** and **fuel amount** options are not used for the unlimited option, so you can set them to whatever you want and it will not affect
> the Tempad.

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the unlimited option is **`tempad:unlimited`**.


## Example use cases

### Normal tempad
```json
{
    "timedoorFuelType": "tempad:unlimited"
}
```

### Advanced tempad
```json
{
    "advancedTimedoorFuelType": "tempad:unlimited"
}
```

Thats it!