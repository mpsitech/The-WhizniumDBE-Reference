BCD frequency generator (bcdfreq_v1_0)
===

**Description**: binary coded decimal frequency generator

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| upper | in | std_logic_vector | 4 |  |
| lower | in | std_logic_vector | 4 |  |
| freq | out | std_logic | 1 |  |

