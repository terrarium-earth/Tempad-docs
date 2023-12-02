# Fluid

> Note! This feature is only available when [Botarium](https://www.modrinth.com/mod/botarium) is installed.

Setting the fuel option for the tempad to be **`tempad:fluid`** will make the Tempad use the fluid fuel option.

The fluid option makes the Tempad consume fluid from the Tempad's internal tank upon opening a time door. The type of fluid
consumed is determined by the fluid tag called `tempad:tempad_liquid_fuel`. The amount of fluid consumed is determined by
the fuel amount. The fuel capacity determines the maximum amount of fluid the Tempad can hold.

## Definitions

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the fluid option is **`tempad:fluid`**.

### Fuel amount

The fuel amount is the amount of fuel the Tempad uses. The fuel amount for the fluid option is the amount of **units of fluid**
the Tempad will consume from the Tempad's internal tank.

### Fuel capacity

The fuel capacity is the maximum amount of fuel the Tempad can hold. The fuel capacity for the fluid option is the amount of
**units of fluid** the Tempad can hold in its internal tank.

> Note! The amount for both the fuel capacity and fuel amount options are in the platform's specific metrics, and the same
> amount of fluid for Fabric and Forge will be different. For example, **81000 units is 1 bucket for Fabric**, but
> **1000 units is 1 bucket for Forge.** Tempad will automatically display the fluid value in millibuckets, with 1 unit being 1/1000th of a bucket.

### Fuel tag

The fuel tag is the fluid tag that determines what fluid the Tempad will consume from the Tempad's internal tank. The fuel tag
for the fluid option is **`tempad:tempad_liquid_fuel`**. By default, this tag contains the fluid `minecraft:lava`.

## Example use cases
To further clarify the differences between fluid units for Fabric and Forge, the examples below will show how to set the
Tempad with a **capacity of 10 buckets**, and **consume 1 bucket** of fluid per time door opened.

### Normal tempad (Forge)

```json
{
    "timedoorFuelType": "tempad:fluid",
    "timedoorFuelAmount": 1000,
    "timedoorFuelCapacity": 10000
}
```

### Normal tempad (Fabric)
```json
{
    "timedoorFuelType": "tempad:fluid",
    "timedoorFuelAmount": 81000,
    "timedoorFuelCapacity": 810000
}
```

### Advanced tempad (Forge)
```json
{
    "advancedTimedoorFuelType": "tempad:fluid",
    "advancedTimedoorFuelAmount": 1000,
    "advancedTimedoorFuelCapacity": 10000
}
```

### Advanced tempad (Fabric)
```json
{
    "advancedTimedoorFuelType": "tempad:fluid",
    "advancedTimedoorFuelAmount": 81000,
    "advancedTimedoorFuelCapacity": 810000
}
```
