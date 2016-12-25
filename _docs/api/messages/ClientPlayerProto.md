---
title: 'ClientPlayerProto'
sort_title: 'client_player_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# ClientPlayerProto

> {{ page.excerpt }}

## Attributes:

- 1: creation_time_ms (int64)
- 2: name (string)
- 5: team (int32)
- 7: tutorial_complete ([TutorialCompletion](../../enums/TutorialCompletion/)) repeated
- 8: player_avatar_proto ([PlayerAvatarProto](../PlayerAvatarProto/))
- 9: max_pokemon_storage (int32)
- 10: max_item_storage (int32)
- 11: daily_bonus_proto ([DailyBonusProto](../DailyBonusProto/))
- 12: equipped_badge_proto ([EquippedBadgeProto](../EquippedBadgeProto/))
- 13: contact_settings_proto ([ContactSettingsProto](../ContactSettingsProto/))
- 14: currency_balance ([CurrencyQuantityProto](../CurrencyQuantityProto/)) repeated
- 15: remaining_codename_claims (int32)
- 16: buddy_pokemon_proto ([BuddyPokemonProto](../BuddyPokemonProto/))
- 17: battle_lockout_end_ms (int64)
- 18: secondary_player_avatar_proto ([PlayerAvatarProto](../PlayerAvatarProto/))

## Enums:

- None

## Referenced by:

- [CodenameResultProto](../CodenameResultProto/)
- [GetPlayerOutProto](../GetPlayerOutProto/)
- [MarkTutorialCompleteOutProto](../MarkTutorialCompleteOutProto/)
- [SetAvatarOutProto](../SetAvatarOutProto/)
- [SetContactSettingsOutProto](../SetContactSettingsOutProto/)
- [SetPlayerTeamOutProto](../SetPlayerTeamOutProto/)

[comment]: <> (YOU CAN EDIT AFTER THIS)
