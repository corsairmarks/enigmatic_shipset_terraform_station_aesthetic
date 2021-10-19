# Overview

Do you like terraform stations from my mod [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084)?  Do you also want to have properly-skinned terraform stations for the [Enigmatic Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2545512457)?  Then this mod is for you!

This mod also addresses phases 2 and three of the Enigmatic habitat not being shaded.

# Changes

Adds a terraform station definition with an active terraforming beam for graphical culture `aoshtai_01`, required for Aesthetic Terraform Stations to apply the correct appearance.

## Compatibility

Should work with practically everything that also works with Enigmatic Shipset and Aesthetic Terraform Stations.  This mod is technically achievement compatible, but its dependencies are not.

Built for Stellaris version 3.1.\* "Lem."

### Required Dependency Mods

[Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084) enables the very old-school terraform stations as visual markers for terraforming planets.

[Enigmatic Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2545512457) for the original graphics and other ship-related code.

### Known Issues

In order to adjust the graphics for the Enigmatic Shipset habitats, it was necessary to overwrite their entity definitions (text files which tell the game how to attach models and textures, and how to shade them).  Overriding a graphics entity causes an error log - expect four entries similar to these:

```
[02:51:29][pdx_entity.cpp:2583]: Duplicate of aoshtai_01_habitat_core_entity added to entity system
[02:51:29][pdx_entity.cpp:2583]: Duplicate of aoshtai_01_habitat_phase_01_entity added to entity system
[02:51:29][pdx_entity.cpp:2583]: Duplicate of aoshtai_01_habitat_phase_02_entity added to entity system
[02:51:29][pdx_entity.cpp:2583]: Duplicate of aoshtai_01_habitat_phase_03_entity added to entity system
```

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/enigmatic_shipset_terraform_station_aesthetic)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.