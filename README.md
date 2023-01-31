# Community Builds

## TODO

Proper json schema put in place, so we have editor support and autocomplete.

## Schema explained

### Skill Order

#### Quick Skill Order

As easy, as defining string with order like this

```json
  "quickSkillOrder": "qew"
```

#### Specific Skill Order

If you want to be really specific about skill order, you can do it with this

```json
  "skillOrder": {
    "Q": [
      1,
      4,
      5,
      7,
      9
    ],
    "W": [
      2,
      8,
      10,
      12,
      13
    ],
    "E": [
      3,
      14,
      15,
      17,
      18
    ],
    "R": [
      6,
      11,
      16
    ]
  }

```
### Runes

Runes use full fledged name.
### Items

itemSets is just array of item recommendations (u can add as many as you want). Inside, you use full fledged names. 

