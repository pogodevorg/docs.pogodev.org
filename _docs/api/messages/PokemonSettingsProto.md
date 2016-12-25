---
title: 'PokemonSettingsProto'
sort_title: 'pokemon_settings_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# PokemonSettingsProto

> {{ page.excerpt }}

## Attributes:

- 1: unique_id ([HoloPokemonId](../../enums/HoloPokemonId/))
- 3: model_scale (float)
- 4: type1 ([HoloPokemonType](../../enums/HoloPokemonType/))
- 5: type2 ([HoloPokemonType](../../enums/HoloPokemonType/))
- 6: camera ([PokemonCameraAttributesProto](../PokemonCameraAttributesProto/))
- 7: encounter ([PokemonEncounterAttributesProto](../PokemonEncounterAttributesProto/))
- 8: stats ([PokemonStatsAttributesProto](../PokemonStatsAttributesProto/))
- 9: quick_moves ([HoloPokemonMove](../../enums/HoloPokemonMove/)) repeated
- 10: cinematic_moves ([HoloPokemonMove](../../enums/HoloPokemonMove/)) repeated
- 11: anim_time (float) repeated
- 12: evolution ([HoloPokemonId](../../enums/HoloPokemonId/)) repeated
- 13: evolution_pips (int32)
- 14: pokemon_class ([HoloPokemonClass](../../enums/HoloPokemonClass/))
- 15: pokedex_height_m (float)
- 16: pokedex_weight_kg (float)
- 17: parent_id ([HoloPokemonId](../../enums/HoloPokemonId/))
- 18: height_std_dev (float)
- 19: weight_std_dev (float)
- 20: km_distance_to_hatch (float)
- 21: family_id ([HoloPokemonFamilyId](../../enums/HoloPokemonFamilyId/))
- 22: candy_to_evolve (int32)
- 23: km_buddy_distance (float)
- 24: buddy_size ([BuddySize](#buddy_size))
- 25: model_height (float)

## Enums:

### BuddySize
- 0: BUDDY_MEDIUM
- 1: BUDDY_SHOULDER
- 2: BUDDY_BIG
- 3: BUDDY_FLYING
- 4: BUDDY_BABY

## Referenced by:

- [GameMasterClientTemplateProto](../GameMasterClientTemplateProto/)

[comment]: <> (YOU CAN EDIT AFTER THIS)
