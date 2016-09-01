---
title: 'CatchPokemonProto'
sort_title: 'catch_pokemon_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# CatchPokemonProto

> {{ page.excerpt }}

## Attributes:

- 1: encounter_id (fixed64)
- 2: pokeball (int32)
- 3: normalized_reticle_size (double)
- 4: spawn_point_guid (string)
- 5: hit_pokemon (bool)
- 6: spin_modifier (double)
- 7: normalized_hit_position (double)

## Enums:

- None

## Referenced by:

- None

[comment]: <> (YOU CAN EDIT AFTER THIS)

## Range:
- normalized_recticle_size: between 0.0 and 2.0
- spin_modifier: between 0.00 and 1.00
- normalized_hit_position: between 0.00 and 1.0

## Attribute Notes:
- encounter_id: The Encounter id of the pokemon, given after sending the EncounterMessage
- pokeball: The type of pokeball to use
- normalized_reticle_size: the size of the catching circle normalized, this is inverse of the size , so the larger the value the smaller the circle (ie the circle size = 2.0-normalized_reticle_size)
- spin_modifier: the amount of spin on the pokeball, 0.00 for no spin and 1.00 for a perfect spin
- normalized_hit_position: The position where the pokeball landed on the Pokemon, this is normalized because pokemon have different sizes. (0.00 for feet, 1.00 for head)

