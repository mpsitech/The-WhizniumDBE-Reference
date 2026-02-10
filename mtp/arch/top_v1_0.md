top module (top_v1_0)
===

**Description**: top-level module (cross-vendor)

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| aresetNNotP | false | external reset polarity |
| fAclk | 100000 | root clock frequency [kHz] |
| aclkIntNotExt | false | root clock origin |
| aclkDiffNotSng | true | root clock endedness |
| clks | mclk | design clocks |
| fClks | 100000 | design clock frequencies [kHz] |
| clkIntNotExts | true | design clock origins |
| clkDiffNotSngs | false | design clock endednesses |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| areset | in | sl | 1 |  |
| aclkp | in | sl | 1 |  |
| aclkn | in | sl | 1 |  |

