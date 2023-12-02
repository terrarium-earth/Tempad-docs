# Energy

> Note! This feature is only available when [Botarium](https://www.modrinth.com/mod/botarium) is installed.

Setting the fuel option for the tempad to be **`tempad:energy`** will make the Tempad use the energy fuel option.

The energy option makes the Tempad consume energy from the Tempad's internal energy buffer upon opening a time door.
The amount of energy consumed is determined by the fuel amount. The fuel capacity determines the maximum amount of energy the Tempad can hold.

## Definitions

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the energy option is **`tempad:energy`**.

### Fuel amount

The fuel amount is the amount of fuel the Tempad uses. The fuel amount for the energy option is the amount of **energy units**
the Tempad will consume from the Tempad's internal energy buffer.


### Fuel capacity

The fuel capacity is the maximum amount of fuel the Tempad can hold. The fuel capacity for the energy option is the amount of
**energy units** the Tempad can hold in its internal energy buffer.

> Note! Tempad's energy system makes use of the Forge Energy API (FE), which is used by many mods. This means that you can use
> Tempad's energy system with other mods that use FE, and vice versa. On Fabric, Tempad uses the Tech Reborn Energy API (E), which
> is also used by many mods. This means that you can use Tempad's energy system with other mods that use E, and vice versa.

## Example use cases

### Normal tempad

```json
{
    "timedoorFuelType": "tempad:energy",
    "timedoorFuelAmount": 1000,
    "timedoorFuelCapacity": 10000
}
```

### Advanced tempad

```json
{
    "advancedTimedoorFuelType": "tempad:energy",
    "advancedTimedoorFuelAmount": 1000,
    "advancedTimedoorFuelCapacity": 10000
}
```

