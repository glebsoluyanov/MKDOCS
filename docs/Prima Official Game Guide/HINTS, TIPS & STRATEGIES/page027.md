![l2_top2.png](../../assets/images/l2_top2.png)
# 25 BASE STATS

### P.ATK
P.Atk is an abbreviation for Physical Attack and determines how much damage you will inflict on a player or monster with a P.Def of 64.
```
[your weapon's P.Atk] x [your level bonus] x [your STR bonus]
```

### P.DEF
P.Def is an abbreviation for Physical Defense and determines how much damage your armor can absorb when a player or monster hits you with their weapon.
```
[your armor's total P.Def] x [your level bonus]
```

### ACCURACY
Accuracy affects your hit/miss ratio with your weapon. The higher your accuracy, the better.
```
([square root of your DEX] x 6) + [your level] + [your weapon's Hit Modifier]
```

**Weapon Hit Modifier**

- *Blunts, Dual Fists: +4.75*
- *Bows, Polearms: -3.75*
- *Others (Swords, Daggers, etc.): no modifier*

### CRITICAL
Critical affects your chance of a critical hit. The higher your Critical, the better. While Critical damage is usually double normal damage, skills like Critical Power can increase the multiplier of a critical hit.
```
[your DEX bonus] x [your weapon's Critical bonus]
```

**Weapon Critical Bonus**

- *Daggers, Bows: 120*
- *Blunts: 40*
- *Others (Dual Fists, Polearms, etc.): 80*

### ATTACK SPEED
Attack speed determines how fast you strike with your weapon. Attack Speeds are directly comparable (for example, Attack Speed 500 is twice as fast as Attack Speed 250), with one exception. Bows have a delay period after ever arrow is fired, which basically cuts a bow’s functional Attack Speed, do just that — divide the displayed number in half.
```
[your DEX bonus] x [your weapon's Attack Speed]
```

**Weapon Attack Speeds**

- *Daggers: 433*
- *Polearms, 2H Swords, 2H Blunts: 325*
- *Bows (effectively 146): 293*
- *Others (Dual Swords, Blunts, etc.): 379*

### M.ATK
M.Atk (Magic Attack) helps determine the amount of damage your weapon and a certain spell will do on a player or monster.
```
[your weapon's M.Atk] x [your level bonus]^2 x [your INT bonus]^2
```

### M.DEF
M.Def (Magic Defense) determines how much magic damage is absorbed by your accessories.
```
[your accessories' combined M.Def] x [your level bonus] x [your MEN bonus]
```

### EVASION
The higher your Evasion, the less likely you are to be hit by an attack. Shields can lower your Evasion, but can also partially block hits.
```
([square root of your DEX] x 6) + [your level]
```

### SPEED
Speed determines how fast you can walk and run. Like Max HP and Max MP, it is the product of a base (unseen) value and a stat modifier — in this case, DEX.
```
[your class's Base Speed] x [your DEX bonus]
```

<div class="compact-table" markdown>

|Class          | Actual Walk | Actual Run|
|---------------|:-----------:|:---------:|
|Elven Fighter  | 103         | 143       |
|Dark Fighter   | 96          | 139       |
|Elven Mystic   | 88          | 126       |
|Human Fighter  | 88          | 126       |
|Dwarven Fighter| 87          | 125       |
|Dark Mystic    | 87          | 125       |
|Orc Mystic     | 72          | 125       |
|Orc Fighter    | 74          | 124       |
|Human Mystic   | 78          | 121       |

</div>

--- 
*Page 25*