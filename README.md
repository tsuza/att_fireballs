<div align="center">
  <h1><code>att_fireballs</code></h1>
  <p>
    <strong>Throw fireballs at your enemies after filling up your charge meter.</strong>
  </p>
  <p style="margin-bottom: 0.5ex;">
    <img
        src="https://img.shields.io/github/downloads/zabaniya001/att_fireballs/total"
    />
    <img
        src="https://img.shields.io/github/last-commit/zabaniya001/att_fireballs"
    />
    <img
        src="https://img.shields.io/github/issues/zabaniya001/att_fireballs"
    />
    <img
        src="https://img.shields.io/github/issues-closed/zabaniya001/att_fireballs"
    />
    <img
        src="https://img.shields.io/github/repo-size/zabaniya001/att_fireballs"
    />
    <img
        src="https://img.shields.io/github/workflow/status/zabaniya001/att_fireballs/Compile%20and%20release"
    />
  </p>
</div>


## Requirements ##
- [TF2 Nosoop's Custom Attributes Framework](https://github.com/nosoop/SM-TFCustAttr)

## Installation ##
1. Grab the latest release from the release page and unzip it in your sourcemod folder.
2. Restart the server or type `sm plugins load att_fireballs` in the console to load the plugin.


## Usage ##
- Give the attribute `fire wizard spells rage` to a weapon in `\config\tf_custom_attributes.txt` or any other way where you add custom attributes to weapons.


### Example

`"fire wizard spells rage"	"max_rage=2000.0 max_damage_25%=500.0 max_damage_50%=1000.0 max_damage_75%=1500.0 max_damage_100%=2000.0"`

```
- max_rage       <- The total amount of damage that the player has to deal to arrive to 100%.
- max_damage_25  <- The maximum amount of dmg it can deal at 25%.  | Speed = Rocket Speed       | Fluctuation = 60% of the max damage
- max_damage_50  <- The maximum amount of dmg it can deal at 50%.  | Speed = Rocket Speed * 0.8 | Fluctuation = 40 of the max damage
- max_damage_75  <- The maximum amount of dmg it can deal at 75%.  | Speed = Rocket Speed * 0.7 | Fluctuation = 20% of the max damage
- max_damage_100 <- The maximum amount of dmg it can deal at 100%. | Speed = Rocket Speed * 0.6 | Fluctuation = 10% of the max damage
```