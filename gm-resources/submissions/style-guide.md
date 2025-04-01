---
layout: default
title: Style Guide
nav_order: 2
parent: Submissions
---

# Style Guide

## Adventures
- See the [adventure submission template](/gm-resources/submissions/adventure-conversions/#submission-template). 
- Please follow the [monsters](#monsters) and [relics](#relics) guidelines for inclusion in the conversion. 

## Relics
Relics utilize the following template:
```
#### Relic Name, # charges
- Note about the cool relic 
- **Recharge**: How does it recharge (if applicable)
```

## Monsters (in an adventure conversion)
- If an ability score is 10, you may omit it if you choose.
- Note the _numbers_ appearing **before** the stats (e.g. 2 HP, 1 Armor)
- The standard monster format is as follows:

```
#### Monster Name
# HP, # Armor, # STR, # DEX, # WIL, weapon1 (d#), item or ability (special details)
- Special 1 (critical damage, special abilities, etc)
- **Critical Damage**: What happens?
```

### Bestiary (the Monsters directory on the website)
- Note the Front Matter (starting with `---`) at the beginning, and the empty line at the end. 
- Note the space between the Monster Name, the stats, and the special entries.
- Include every ability score, _even if they are only 10_. 
- For an example, see the raw text [here](https://github.com/yochaigal/cairn/blob/main/resources/monsters/acolyte.md)
- Monster submissions to the website (distinct from an adventure conversion) must utilize the following format.


```
---
layout: default
parent: Monsters
grand_parent: GM Resources
---

# Monster Name

# HP, # Armor, # STR, # DEX, # WIL, weapon1 (d#), item or ability (special details)

- Special 1 (critical damage, special abilities, etc)
- **Critical Damage**: What happens?

```
