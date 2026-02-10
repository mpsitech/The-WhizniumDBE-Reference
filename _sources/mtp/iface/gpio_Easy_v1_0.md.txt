GPIO controller (gpio_Easy_v1_0)
===

**Description**: general purpose I/O

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| w | 32 | width 8/16/32 [bit] |
| threeNotInout | false | tri-state buffer configuration |
| bidirNotUnidir | false | directionality |
| inNotOut | false | direction for unidirectional |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| bits | inout | slvdn | 32 |  |
| bits_in | in | slvdn | 32 |  |
| bits_out | out | slvdn | 32 |  |
| bits_tri | out | slvdn | 32 |  |

