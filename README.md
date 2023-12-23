# Community Builds

Community League of Legends ARAM builds repository for [aramonly.com](https://www.aramonly.com). 

## JSON Schema

To make it easier for anyone to prepare new builds, JSON schema has been added. Please import it in your IDE to use it.

### Note

Schema was changed some time ago (Tags field is removed — for example). Please use build-schema.json.

## Schema explained

### Skill Order

#### Quick Skill Order

As easy as defining a string with order like this

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

There's autocomplete support for runes (thanks to JSON schema). It takes sanitized Rune names. Validation is done outside of schema.

### Items

There's autocomplete support for items (thanks to JSON schema). ItemSets is just an array of item recommendations (u can add as many as you want). Inside, you use full-fledged names. 

