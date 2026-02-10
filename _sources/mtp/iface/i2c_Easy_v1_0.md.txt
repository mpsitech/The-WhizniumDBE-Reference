I2C master (i2c_Easy_v1_0)
===

**Description**: I2C transceiver

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| threeNotInout | false | tri-state buffer configuration |


### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |
| clkFastNotStd | sl | 1 | 1 | 1Mbps/400kbps vs. 100kbps |
| clkFastplusNotFast | sl | 1 | 0 | 1Mbps vs. 400kbps |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| scl | inout | sl | 1 |  |
| scl_in | in | sl | 1 |  |
| scl_out | out | sl | 1 |  |
| scl_tri | out | sl | 1 |  |
| sda | inout | sl | 1 |  |
| sda_in | in | sl | 1 |  |
| sda_out | out | sl | 1 |  |
| sda_tri | out | sl | 1 |  |

