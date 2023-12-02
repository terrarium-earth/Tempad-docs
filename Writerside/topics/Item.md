# Item

Setting the fuel option for the tempad to be **`tempad:item`** will make the Tempad use the item fuel option.

The item option makes the Tempad consume items from the player's inventory upon opening a time door. The type of item
consumed is determined by an item tag called `tempad:tempad_fuel`. This will always consume 1 item per time door opened.

## Definitions

> Note! The **fuel capacity** and **fuel amount** options are not used for the item option, so you can set them to whatever you want and it will not affect
> the Tempad.

### Fuel type

The fuel type is the type of fuel the Tempad uses. The fuel type for the item option is **`tempad:item`**.

### Fuel tag

The fuel tag is the item tag that determines what item the Tempad will consume from the player's inventory. The fuel tag
for the item option is **`tempad:tempad_fuel`**. By default, this tag contains the items `minecraft:ender_pearl` and
`minecraft:ender_eye`.

## Example use cases

> Note! The fuel tag is used for both the normal and advanced Tempad.

### Normal tempad
```json
{
    "timedoorFuelType": "tempad:item",
}
```

### Advanced tempad
```json
{
    "advancedTimedoorFuelType": "tempad:item",
}
```

