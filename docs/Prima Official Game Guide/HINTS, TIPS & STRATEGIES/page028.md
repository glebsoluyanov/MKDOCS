![l2_top.png](/assets/images/l2_top.png)
# 26 BASE STATS

### Casting Speed

Casting speed is how fast you cast spells. All casting speeds are comparable to each other (Casting speed 500 is twice as fast as casting speed 250).
```
166.5 x [your DEX bonus]
```

### Carrying Capacity

Carrying capacity is how much you can carry. As you carry more and more, you begin to be penalized. This is represented by a color-change from yellow to orange to red on your carrying capacity bar. For example, at 50% capacity, your HP/MP regeneration rates are slower.
```
52,000 x [your CON bonus]
```

### Physical Attack Damage

Roughly speaking, if a strike hits, the damage it inflicts is:
```
[attacker's P.Atk] x 70 / [defender's P.Def]
```

This can be further modified by several factors, including a purely random damage modifier (of about +/- 5%) and of course, whether a critical hit is scored. (Dual Fist and Daggers have the lowest random damage variation. Blunt weapons have the highest variation.)

### Magical Attack Damage
```
(square root of [attacker's M.Atk/defender's M.Def])
x [skill's Power] x 91
```

## Creature Combat Stats

Most of the useful stats for each creature are listed in the Monsters chapter. However, those stats don't include their P.Atk, P.Def, M.Atk and M.Def. That's because these stats are (in general) almost totally determined by the creature's level, so we've listed those values here, in a single table. These are average stats, but they are correct for over 95% of the creatures in Lineage II. There are a few exceptions to that rule of thumb:

- An archer's P.Atk is about 120% higher (but archers tend to have slower attack speeds).
- Mercenaries have significantly higher stats.
- Castle guard stats can be significantly higher, especially their attack stats.

- Aden guard P.Atk stats can be as much as triple the normal.
- Boss stats tend to be higher.

| Lvl | P.Atk  | P.Def   | M.Atk | M.Def |
|-----|--------|---------|-------|-------|
| 1   | 4      | 39-40   | 2-3   | 31    |
| 2   | 9-10   | 41-42   | 3     | 33    |
| 3   | 11-12  | 43      | 3     | 35    |
| 4   | 12-13  | 45-47   | 3     | 37    |
| 5   | 13     | 48-49   | 4     | 38    |
| 6   | 14-15  | 50-52   | 5     | 41    |
| 7   | 17-18  | 52-54   | 5     | 42    |
| 8   | 18-19  | 55-57   | 6     | 45    |
| 9   | 21-22  | 57-59   | 7     | 46    |
| 10  | 22-24  | 60-67   | 8     | 49    |
| 11  | 25-27  | 64-72   | 8     | 51    |
| 12  | 26-30  | 66-72   | 9     | 53    |
| 13  | 30-33  | 69-76   | 11    | 56    |
| 14  | 33-35  | 73-80   | 12    | 59    |
| 15  | 36-39  | 75-83   | 13    | 61    |
| 16  | 40-44  | 79-87   | 14    | 64    |
| 17  | 43-48  | 82-91   | 16    | 67    |
| 18  | 46-52  | 86-95   | 18    | 70    |
| 19  | 48-58  | 90-99   | 20    | 73    |
| 20  | 57-62  | 93-103  | 22    | 76    |
| 21  | 62-68  | 97-107  | 24    | 79    |
| 22  | 67-74  | 102-112 | 27    | 82    |
| 23  | 73-81  | 106-117 | 30    | 85    |
| 24  | 81-89  | 110-122 | 33    | 90    |
| 25  | 87-97  | 115-127 | 36    | 93    |
| 26  | 95-104 | 120-132 | 39    | 97    |
| 27  | 103-114| 125-138 | 43    | 101   |
| 28  | 112-123| 129-142 | 47    | 105   |
| 29  | 121-134| 135-148 | 52    | 110   |
| 30  | 131-144| 140-154 | 57    | 113   |
| 31  | 142-156| 145-160 | 61    | 118   |
| 32  | 153-168| 151-166 | 67    | 122   |

| Lvl | P.Atk   | P.Def   | M.Atk | M.Def |
|-----|---------|---------|-------|-------|
| 33  | 165-181 | 157-173 | 73    | 127   |
| 34  | 178-196 | 162-179 | 79    | 132   |
| 35  | 191-211 | 168-186 | 86    | 137   |
| 36  | 205-226 | 175-192 | 94    | 141   |
| 37  | 220-243 | 181-187 | 101   | 146   |
| 38  | 237-260 | 187-194 | 109   | 152   |
| 39  | 254-279 | 194-200 | 118   | 157   |
| 40  | 272-298 | 201-221 | 127   | 163   |
| 41  | 291-319 | 208-228 | 137   | 168   |
| 42  | 311-342 | 214-237 | 148   | 174   |
| 43  | 332-365 | 223-245 | 159   | 180   |
| 44  | 354-389 | 230-253 | 170   | 186   |
| 45  | 376-414 | 237-261 | 183   | 193   |
| 46  | 401-440 | 245-270 | 197   | 199   |
| 47  | 425-468 | 252-278 | 210   | 205   |
| 48  | 452-498 | 261-287 | 225   | 211   |
| 49  | 480-528 | 269-296 | 241   | 219   |
| 50  | 508-560 | 278-305 | 257   | 225   |
| 51  | 539-593 | 285-315 | 274   | 231   |
| 52  | 570-626 | 294-324 | 292   | 239   |
| 53  | 601-662 | 303-333 | 311   | 245   |
| 54  | 634-698 | 311-343 | 331   | 253   |
| 55  | 670-736 | 321-352 | 351   | 260   |
| 56  | 704-776 | 330-362 | 372   | 268   |
| 57  | 742-816 | 340-373 | 394   | 275   |
| 58  | 779-859 | 348-384 | 417   | 283   |
| 59  | 817-902 | 358-395 | 441   | 290   |
| 60  | 860-945 | 368-405 | 466   | 299   |
| 61  | 901-991 | 378-415 | 492   | 306   |
| 62  | 941-1038| 388-426 | 518   | 315   |
| 63  | 986-1085| 398-437 | 545   | 322   |
| 64  | 1031-1134| 408-448 | 573   | 331   |
| 65  | 1075-1184| 417-459 | 602   | 338   |
| 66  | 1121-1235| 428-470 | 633   | 347   |
| 67  | 1168-1286| 438-481 | 663   | 356   |
| 68  | 1217-1337| 448-492 | 695   | 364   |
| 69  | 1248-1391| 459-503 | 726   | 373   |
| 70  | 1312-1444| 469-514 | 760   | 381   |