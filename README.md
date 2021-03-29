# Fireballs Attribute

Custom Attribute using Nosoop's [custom attributes framework](https://github.com/nosoop/SM-TFCustAttr). 

This custom attribute lets you throw fireballs! You've become a wizard, Harry!
You basically have a fuel system. Every 25% you can throw a fireball. The damage and speed depend on how much fuel you have. The more fuel you have, the more damage but also less speed it has. The damage fluctuates ( so like, it can deal from 300 dmg up to 500 dmg ), however, the more fuel it has the less it fluctuates.

```
"fire wizard spells rage"				"max_rage=2000.0 max_damage_25%=500.0 max_damage_50%=1000.0 max_damage_75%=1500.0 max_damage_100%=2000.0"
```

These are its arguments. You can change 'em however it pleases you. 
```
- max_rage       <- The total amount of damage that the player has to deal to arrive to 100%.
- max_damage_25  <- The maximum amount of dmg it can deal at 25%.  | Speed = Rocket Speed       | Fluctuation = 60% of the max damage
- max_damage_50  <- The maximum amount of dmg it can deal at 50%.  | Speed = Rocket Speed * 0.8 | Fluctuation = 40 of the max damage
- max_damage_75  <- The maximum amount of dmg it can deal at 75%.  | Speed = Rocket Speed * 0.7 | Fluctuation = 20% of the max damage
- max_damage_100 <- The maximum amount of dmg it can deal at 100%. | Speed = Rocket Speed * 0.6 | Fluctuation = 10% of the max damage
```

https://youtu.be/x2La9ud_KRw Here is a video if you're interested to see how it works first

Tested it on Nosoop's [Custom Weapon X](https://github.com/nosoop/SM-TFCustomWeaponsX) and it works without any problems.

This plugin uses Nosoop's [Ninja](https://github.com/nosoop/NinjaBuild-SMPlugin) template. Easy to organize everything and build releases. I'd recommend to check it out.

Please, this is the first version of this plugin. If you find any issues, make sure to open an issue to let me know!

Also I've got no clue how to properly format this.
