---
level: 1
proficiency_bonus: 3
---
```badges
items:
  - label: Name
    value: 'PLAYER NAME'
```
```badges
items:
  - label: Class
    value: 'Druid'
  - label: Race
    value: 'DragonBorn'
  - label: Level
    value: '{{ frontmatter.level }}'
```
```badges
items:
  - label: Initiative
    value: '+{{ modifier abilities.dexterity }}'
  - label: AC
    value: '{{ add 10 (modifier abilities.dexterity) }}'
  - label: Spell Attack
    value: '{{ add 10 frontmatter.proficiency_bonus (modifier abilities.intelligence) }}'
```

```ability
abilities:
  strength: 14
  dexterity: 16
  constitution: 13
  intelligence: 12
  wisdom: 15
  charisma: 8

proficiencies:
  - dexterity
  - intelligence
```

```skills
proficiencies:
  - stealth
  - investigation
  - perception

expertise:
  - stealth
```

```badges
items:
  - label: Passive Perception
    value: '{{ add 10 frontmatter.proficiency_bonus (modifier abilities.wisdom) }}'
  - label: Passive Investigation
    value: '{{ add 10 frontmatter.proficiency_bonus (modifier abilities.intelligence) }}'
  - label: Passive Insight
    value: '{{ add 10 frontmatter.proficiency_bonus (modifier abilities.wisdom) }}'
```

#### Background


#### Quests

