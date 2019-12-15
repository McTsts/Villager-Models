# Villager-Models
A Minecraft Resource Pack which has all models for villagers!

## Contents
This resource pack has a model for every villager that is in the game as well as some combinations that don't appear in Minecraft.
This pack includes all combination of types, professions, and profession levels, where each of those can also be none.

![alt text](https://github.com/McTsts/Villager-Models/blob/master/models.png)
Each row is one type. Bottom is model version, above is minecraft version (if it exists).

## How to Use
A villager model can be obtained by using
> give @s minecraft:emerald{CustomModelData:**VILLAGER ID**}

For this the values of model, type, profession and level need to be looked up in the following lists.

Villager ID consists is created by concatenating Model, Type, Profession and Level and then converting it to a number.

e.g. the Villager ID for a Standing Swamp Fisherman with Level 2 (Stone) would be:

- Model => Standing => 00
- Type => Swamp => 06
- Profession => Fisherman => 06
- Level => 2/Stone => 02

Concatenating this gives `00060602` which as a number is `60602`, so the villager can be obtained via:
> give @s minecraft:emerald{CustomModelData:60602}



#### Model
- 00 Standing
- 01 Looking Up
- 02 Looking Down
- 03 Shaking Head (1)
- 04 Shaking Head (2)
- 05 Walking (1)
- 06 Walking (2)

#### Type
- 00 None
- 01 Desert
- 02 Jungle
- 03 Plains 
- 04 Savanna
- 05 Snow 
- 06 Swamp
- 07 Taiga

#### Profession
- 00 None
- 01 Armorer
- 02 Butcher
- 03 Cartographer
- 04 Cleric
- 05 Farmer
- 06 Fisherman
- 07 Fletcher
- 08 Leatherworker
- 09 Librarian
- 10 Mason
- 11 Nitwit
- 12 Shepherd
- 13 Toolsmith
- 14 Weaponsmith

#### Profession Level
- 00 None
- 01 Stone
- 02 Iron
- 03 Gold
- 04 Emerald
- 05 Diamond

## How to modify
`assets\minecraft\models\item\villager_parent\villager.json` is the parent to all models and can be used to modify the display of the villagers.

## Credit
Use this for whatever you want.
Made by McTsts. Credit is not required but appreciated.
