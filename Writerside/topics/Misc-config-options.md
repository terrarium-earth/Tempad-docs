# Misc config options

This page explains the config options in the `tempad.jsonc` file in the `config` folder of your minecraft instance that
don't define the fuel options for the tempad. If you want to learn about the fuel options, go to
[Fuel options page](Fuel-options.md).

distanceFromPlayer
: Type: Integer
: Default: 3
: This is the distance in blocks that the Timedoor will be from the player when it is opened. The default is 3

timedoorWaitTime
: Type: Integer
: Default: 60
: This is the amount of time, in ticks, that the Timedoor will wait before closing itself after the owner has gone
through it.
: Remember that 20 ticks = 1 second

timedoorAddWaitTime
: Type: Integer
: Default: 40
: This is the amount of time, in ticks, that the Timedoor will add to its wait time to after an entity other than the owner
has gone through it.
: Remember that 20 ticks = 1 second

allowInterdimensionalTravel
: Type: Boolean
: Default: true
: This is whether or not the Tempad will allow timedoors to be opened to locations in other dimensions.

allowExporting
: Type: Boolean
: Default: true
: This is whether or not the Tempad will allow players to create Location Cards from locations.

consumeCooldown
: Type: Boolean
: Default: true
: This is whether or not the Tempad will consume the cooldown of the Tempad when a location is exported to a Location Card.

