## Implement Merchant Tier System (Bronze/Silver/Gold)

- Added `MerchantTier` enum and `MERCHANT_TIERS` configuration.
- Updated fee calculation utilities to reference the new merchant tier system.
- Removed unused higher tiers (Platinum, Diamond, etc.) and associated tests.
- Adjusted documentation/comments accordingly.

This change introduces flexible pricing based on merchant volume, enabling larger partners to benefit from reduced fees.
