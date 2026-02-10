RGB LED (rgbled_v1_0)
===

**Description**: driver for RGB LED

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| rgb | in | std_logic_vector | 24 |  |
| r | out | std_logic | 1 |  |
| g | out | std_logic | 1 |  |
| b | out | std_logic | 1 |  |

