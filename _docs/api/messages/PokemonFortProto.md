---
title: 'PokemonFortProto'
sort_title: 'pokemon_fort_proto'
category: API
excerpt: FIXME
---

# PokemonFortProto

> FIXME

## Attributes:

- 1: fort_id (string)
- 2: last_modified_ms (int64)
- 3: latitude (double)
- 4: longitude (double)
- 5: team (int32)
- 6: guard_pokemon_id (int32)
- 7: guard_pokemon_level (int32)
- 8: enabled (bool)
- 9: fort_type ([FortType](../../enums/FortType/))
- 10: gym_points (int64)
- 11: is_in_battle (bool)
- 12: active_fort_modifier ([Item](../../enums/Item/)) 
- 13: active_pokemon ([MapPokemonProto](../MapPokemonProto/))
- 14: cooldown_complete_ms (int64)
- 15: sponsor ([Sponsor](#sponsor))
- 16: rendering_type ([RenderingType](#rendering_type))

## Enums:

### Sponsor
- 0: UNSET
- 1: MCDONALDS
- 2: POKEMON_STORE
### RenderingType
- 0: DEFAULT
- 1: INTERNAL_TEST

## Referenced by:

- [ClientMapCellProto](../ClientMapCellProto/)
- [GymStateProto](../GymStateProto/)
- [PlayerUpdateOutProto](../PlayerUpdateOutProto/)
