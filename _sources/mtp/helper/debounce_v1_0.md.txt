de-bouncer (debounce_v1_0)
===

**Description**: signal de-bouncer

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| invert | _bool |  | false |  |
| tdead | nat |  | 100 | in tkclk clocks |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| tkclk | in | std_logic | 1 |  |
| noisy | in | std_logic | 1 |  |
| clean | out | std_logic | 1 |  |

