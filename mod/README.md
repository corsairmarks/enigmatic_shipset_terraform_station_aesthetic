# Overview

Do you like terraform stations from my mod [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084)?  Do you also want to have properly-skinned terraform stations for the [Enigmatic Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2545512457)?  Then this mod is for you!

MadamLava hand-crafted a special model just for terraform stations - available only with this mod!

# Changes

Adds a terraform station definition with an active terraforming beam for graphical culture `aoshtai_01`, required for Aesthetic Terraform Stations to apply the correct appearance.

## Compatibility

Should work with practically everything that also works with Enigmatic Shipset and Aesthetic Terraform Stations.

Built for Stellaris version 3.7 "Canis Minor" and backwards-compatible with versions 3.6 "Orion," 3.5 "Fornax," 3.4 "Cepheus," 3.3 "Libra," 3.2 "Herbert," 3.1 "Lem", and 3.0 "Dick."  Not compatible with achievements, but neither are the dependencies.

### Required Dependency Mods

* [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084) enables the very old-school terraform stations as visual markers for terraforming planets
* [Enigmatic Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2545512457) for the original graphics and other ship-related code

## Changelog

* 1.0.0 Initial version
* 1.1.0 Mark as compatible with Stellaris version 3.2 "Herbert" - no script changes
* 1.2.0 New, unique model for the Enigmatic terraform station - made by MadamLava herself!
* 1.3.0 Mark as compatible with Stellaris version 3.3 "Libra" - no script changes
* 1.4.0 Mark as compatible with Stellaris version 3.4 "Cepheus" - no script changes
* 1.5.0 Mark as compatible with Stellaris version 3.6 "Orion" - no script changes
* 1.6.0 Add compatibility trigger for other mods to check whether this one is active
* 1.7.0 Mark as compatible with Stellaris version 3.7 "Canis Minor" - no script changes

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/enigmatic_shipset_terraform_station_aesthetic)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.