---
title: 'BattleActionProto'
sort_title: 'battle_action_proto'
category: API
excerpt: FIXME
---

# BattleActionProto

> FIXME

## Attributes:

- 1: type ([ActionType](#action_type))
- 2: action_start_ms (int64)
- 3: duration_ms (int32)
- 5: energy_delta (int32)
- 6: attacker_index (int32)
- 7: target_index (int32)
- 8: active_pokemon_id (fixed64)
- 9: joined_player ([BattleParticipantProto](../BattleParticipantProto/))
- 10: battle_results ([BattleResultsProto](../BattleResultsProto/))
- 11: damage_window_start_ms (int64)
- 12: damage_window_end_ms (int64)
- 13: quit_player ([BattleParticipantProto](../BattleParticipantProto/))
- 14: target_pokemon_id (fixed64)

## Enums:

### ActionType
- 0: UNSET
- 1: ATTACK
- 2: DODGE
- 3: SPECIAL_ATTACK
- 4: SWAP_POKEMON
- 5: FAINT
- 6: PLAYER_JOIN
- 7: PLAYER_QUIT
- 8: VICTORY
- 9: DEFEAT
- 10: TIMED_OUT

## Referenced by:

- [AttackGymProto](../AttackGymProto/)
- [BattleLogProto](../BattleLogProto/)
