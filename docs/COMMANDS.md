# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/bonds` | Bond vault â€” issue bonds, collect coupons, redeem certificates | `` | `/<command> [create <amount/root>]` |
| `/rootbonds` | Admin reload for Root-Bonds | `rootbonds.reload` | `/<command> reload` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootbonds.use` | Open /bonds and issue bonds via GUI | `true` |
| `rootbonds.reload` | Reload root-bonds.yml | `op` |

