![l2_top.png](../assets/images/l2_top.png)
# 24 BASE STATS
## BASE STATS

Base stats determine your character’s strengths and weaknesses. Your base stats are chosen when you choose your race and class at character creation. As of Chronicle 1, the only way to change any of them is by equipping certain armor sets (pieces of armor that have a special bonus when worn together). A list of armor sets and their effects can be found on p. 128.

Base stats also impact the success rate of some skills. For example, skills like Stun (based on CON) or Dryad Root (based on DEX) are more effective with certain races than others because the influential base stat isn’t the same.

Each base stat is listed below, with the other stats it influences, and its modifiers. Stats that also appear in your Character window are listed before the “/”. Modifiers are used to determine the effects they have on other stats, as described in the next section.

### STR (STRENGTH)
!!! STRENGTH
    **Influences.** P.Atk / Melee damage, skills like Curse: Weakness

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM | OF   | OM  | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:---:|:----:|:---:|:----:|
    | +19% | -10% | +13% | -11% | +22% | -8% | +20% | -2% | +18% |

    </div>

### CON (CONSTITUTION)
!!! CONSTITUTION
    **Influences.** HP, Carrying Capacity / HP regeneration, skills like Shield Stun

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM  | OF   | OM   | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
    | +58% | +24% | +42% | +20% | +34% | +19% | +67% | +32% | +62% |

    </div>

### DEX (DEXTERITY)
!!! DEXTERITY
    **Influences.** Accuracy, Critical, Attack Speed, Movement Speed, Evasion / Skills like Dryad Root

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM  | OF   | OM   | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
    | +10% | +1% | +15% | +4% | +14% | +3% | +6% | +4% | +9% |

    </div>

### INT (INTELLIGENCE)
!!! INTELLIGENCE
    **Influences.** M.Atk / Magic damage

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM  | OF   | OM   | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
    | -19% | +21% | -15% | +12% | -12% | +28% | -23% | -1% | -20% |

    </div>

### MEN
!!! MEN
    **Influences.** MP, M.Def / MP regeneration, skills like Poison

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM  | OF   | OM   | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
    | +28% | +48% | +30% | +49% | +30% | +45% | +31% | +52% | +31% |

    </div>

## WIT
!!! WIT
    **Influences.** Casting Speed / Skills like Sleep

    **Modifiers**
    <div class="compact-table tw100" markdown>

    | HF   | HM   | EF   | EM   | DEF  | DEM  | OF   | OM   | DwF  |
    |:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
    | -36% | 0% | -25% | +16% | -32% | -5% | -32% | -22% | -39% |

    </div>

## CHARACTER STATS

Character stats are influenced by your base stats, your level and your equipment. As you gain experience, skills and items, you see these numbers grow, and they help you decide which equipment to use in certain situations.

Listed below are all your stats on the Character window, what contributes to that number, formulas for how they’re determined and what they mean.

Note that each class also has passive and active skills that can affect their character stats.

**Level Modifier** is a percentage equal to `[your level – 11]`
For example, a Level 30 character has a level modifier of `+19% (30 – 11)`, while a Level 1 character has a modifier of `-10% (1 – 11)`.

### MAX HP AND MAX MP
These are determined by your class, your level and your CON (for HP) and MEN (for MP). Higher CON and MEN give better HP and MP, but since these base stats rarely change, you’ll rarely see the direct effect of these modifiers.

`Max HP = [your current base HP] x [your CON bonus]`

`Max MP = [your current base MP] x [your MEN bonus]`