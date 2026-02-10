General-purpose signal tracker (gptrack_Easy_v1_0)
===

**Description**: general purpose signal tracker (cross-vendor)

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| trkclk | mclk | clock (ex. pixclk) |
| ratioTrkclk | 1.0 | track clock ratio wrt. master clock (ex. 1.25) |
| sizeSeqbuf | 2 | sequence buffer size [kB] |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| resetTrkclk | in | sl | 1 |  |
| trkclk | in | sl | 1 |  |

