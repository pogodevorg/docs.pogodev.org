---
title: 'BattleLogProto'
sort_title: 'battle_log_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# BattleLogProto

> {{ page.excerpt }}

## Attributes:

- 1: state ([State](#state))
- 2: battle_type ([BattleType](#battle_type))
- 3: server_ms (int64)
- 4: battle_actions ([BattleActionProto](../BattleActionProto/)) repeated
- 5: battle_start_ms (int64)
- 6: battle_end_ms (int64)

## Enums:

### BattleType
- 0: BATTLE_TYPE_UNSET
- 1: NORMAL
- 2: TRAINING
### State
- 0: STATE_UNSET
- 1: ACTIVE
- 2: VICTORY
- 3: DEFEATED
- 4: TIMED_OUT

## Referenced by:

- [AttackGymOutProto](../AttackGymOutProto/)
- [StartGymBattleOutProto](../StartGymBattleOutProto/)

[comment]: <> (YOU CAN EDIT AFTER THIS)
