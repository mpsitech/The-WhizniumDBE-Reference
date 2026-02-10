neo random number generator (neotrng_v1_0)
===

**Description**: true random number generator based on https://github.com/stnolting/neoTRNG

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| NUM_CELLS | nat |  | 3 | total number of ring-oscillator cells |
| NUM_INV_START | nat |  | 3 | number of inverters in first cell (short path), has to be odd |
| NUM_INV_INC | nat |  | 2 | number of additional inverters in next cell (short path), has to be even |
| NUM_INV_DELAY | nat |  | 2 | additional inverters to form cell's long path, has to be even |
| POST_PROC_EN | _bool |  | false | implement post-processing for advanced whitening when true |
| IS_SIM | _bool |  | false | for simulation only! |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| clk_i | in | std_logic | 1 |  |
| enable_i | in | std_logic | 1 |  |
| data_o | out | std_logic_vector | 8 |  |
| valid_o | out | std_logic | 1 |  |

