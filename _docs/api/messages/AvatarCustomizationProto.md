---
title: 'AvatarCustomizationProto'
sort_title: 'avatar_customization_proto'
category: API
excerpt: 'FIXME: Add a description'
---

[comment]: <> (THIS PART IS GENERATED - AKA DON'T EDIT THIS PART MANUALLY)

# AvatarCustomizationProto

> {{ page.excerpt }}

## Attributes:

- 1: enabled (bool)
- 2: avatar_type ([PlayerAvatarType](../../enums/PlayerAvatarType/))
- 3: slot (Slot) repeated
- 4: bundle_name (string)
- 5: asset_name (string)
- 6: group_name (string)
- 7: sort_order (int32)
- 8: unlock_type ([AvatarCustomizationUnlockType](#avatar_customization_unlock_type))
- 9: promo_type ([AvatarCustomizationPromoType](#avatar_customization_promo_type)) repeated
- 10: unlock_badge_type ([HoloBadgeType](../../enums/HoloBadgeType/))
- 11: iap_sku (string)
- 12: unlock_badge_level (int32)

## Enums:

### AvatarCustomizationPromoType
- 0: UNSET_PROMO_TYPE
- 1: SALE
- 2: FEATURED
### AvatarCustomizationUnlockType
- 0: UNSET_UNLOCK_TYPE
- 1: DEFAULT
- 2: MEDAL_REWARD
- 3: IAP_CLOTHING

## Referenced by:

- [GameMasterClientTemplateProto](../GameMasterClientTemplateProto/)

[comment]: <> (YOU CAN EDIT AFTER THIS)
