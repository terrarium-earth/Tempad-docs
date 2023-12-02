# Fuel options

This page will explain to you how to configure Tempad's fuel options in Tempad's config during and after version 1.20.1

## Configuring the correct tempad

Tempad has 2 tempads in it. The one on the **left is the normal tempad**, which by default has a recipes thats accessible to
players. The one on the **right is the advanced tempad**, AKA the He who remains tempad. This one is not craftable,
only accessible from the end city.

![tempads.png](tempads.png)

Both of these tempads have the same 3 options you can configure. Below is a table explaining what each option does and
the names for those options on the respective tempad so you know which one to configure.

> Note! All of the options discussed below are found in the `tempad.jsonc` file in the `config` folder of your
> minecraft instance.

Fuel type
: Type: String
: This is the type of fuel the tempad uses. The default for the normal tempad is `tempad:timer`. The default for the
advanced tempad is `tempad:unlimted`.
```jsonc
{
    "timedoorFuelType": "tempad:timer", // Normal tempad
    "advancedTimedoorFuelType": "tempad:unlimited" // Advanced tempad
}
```

Fuel amount
: Type: Integer
: This is the amount of fuel the tempad uses. This value may or may not be used, and has different meanings depending
on the fuel type. The default for the normal tempad is 180. The default for the advanced tempad is 1.
```jsonc
{
    "timedoorFuelAmount": 180, // Normal tempad
    "advancedTimedoorFuelAmount": 1 // Advanced tempad
}
```

Fuel capacity
: Type: Integer
: This is the amount of fuel the tempad can hold. This value may or may not be used, and has different meanings
depending on the fuel type. The default for the normal tempad is 1000. The default for the advanced tempad is 1000.
```jsonc
{
    "timedoorFuelCapacity": 1000, // Normal tempad
    "advancedTimedoorFuelCapacity": 1000 // Advanced tempad
}
```