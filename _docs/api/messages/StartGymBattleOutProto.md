---
title: 'StartGymBattleOutProto'
sort_title: 'start_gym_battle_out_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# StartGymBattleOutProto

> {{ page.excerpt }}

## Attributes:

- 1: result ([Result](#result))
- 2: battle_start_ms (int64)
- 3: battle_end_ms (int64)
- 4: battle_id (string)
- 5: defender ([BattleParticipantProto](../BattleParticipantProto/))
- 6: battle_log ([BattleLogProto](../BattleLogProto/))
- 7: attacker ([BattleParticipantProto](../BattleParticipantProto/))

## Enums:

### Result
- 0: UNSET
- 1: SUCCESS
- 2: ERROR_GYM_NOT_FOUND
- 3: ERROR_GYM_NEUTRAL
- 4: ERROR_GYM_WRONG_TEAM
- 5: ERROR_GYM_EMPTY
- 6: ERROR_INVALID_DEFENDER
- 7: ERROR_TRAINING_INVALID_ATTACKER_COUNT
- 8: ERROR_ALL_POKEMON_FAINTED
- 9: ERROR_TOO_MANY_BATTLES
- 10: ERROR_TOO_MANY_PLAYERS
- 11: ERROR_GYM_BATTLE_LOCKOUT
- 12: ERROR_PLAYER_BELOW_MINIMUM_LEVEL
- 13: ERROR_NOT_IN_RANGE

## Referenced by:

- None

[comment]: <> (YOU CAN EDIT AFTER THIS)
