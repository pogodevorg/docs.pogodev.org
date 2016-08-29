---
title: 'ClientMapCellProto'
sort_title: 'client_map_cell_proto'
category: API
excerpt: 'Geographical "zone" containing objects like pokemons, gyms and pokestops.'
description: 'Geographical "zone" containing objects like pokemons, gyms and pokestops.'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# ClientMapCellProto

> Geographical "zone" containing objects like pokemons, gyms and pokestops.

## Protocol

### Attributes:

- 1: [`s2_cell_id`](#s2cellid) (uint64)
- 2: [`as_of_time_ms`](#asoftimems) (int64)
- 3: [`fort`](#fort) ([PokemonFortProto](../PokemonFortProto/)) repeated
- 4: [`spawn_point`](#spawnpoint) ([ClientSpawnPointProto](../ClientSpawnPointProto/)) repeated
- 5: [`wild_pokemon`](#wildpokemon) ([WildPokemonProto](../WildPokemonProto/)) repeated
- 6: [`deleted_object`](#deletedobject) (string) repeated
- 7: [`is_truncated_list`](#istruncatedlist) (bool)
- 8: [`fort_summary`](#fortsummary) ([PokemonSummaryFortProto](../PokemonSummaryFortProto/)) repeated
- 9: [`decimated_spawn_point`](#decimatedspawnpoint) ([ClientSpawnPointProto](../ClientSpawnPointProto/)) repeated
- 10: [`catchable_pokemon`](#catchablepokemon) ([MapPokemonProto](../MapPokemonProto/)) repeated
- 11: [`nearby_pokemon`](#nearbypokemon) ([NearbyPokemonProto](../NearbyPokemonProto/)) repeated

### Enums:

- None

### Referenced by:

- [GetMapObjectsOutProto](../GetMapObjectsOutProto/)

[comment]: <> (YOU CAN EDIT AFTER THIS)

## Attributes

### `s2_cell_id`

S2 geographic area that the cell covers (http://s2map.com/) (https://code.google.com/archive/p/s2-geometry-library/)

### `as_of_time_ms`

### `fort`

### `spawn_point`

### `wild_pokemon`

Pokemon within 2 steps or less.

### `deleted_object`

### `is_truncated_list`

### `fort_summary`

### `decimated_spawn_point`

### `catchable_pokemon`

Pokemon within 1 step or none.

### `nearby_pokemon`

Pokemon farther away than 2 steps, but still in the area.
