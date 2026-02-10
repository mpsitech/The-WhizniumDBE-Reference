SPI slave (spislave_v2_0)
===

**Description**: SPI slave with AXI stream interface

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| cpol | sl |  | 0 | clock polarity |
| cpha | sl |  | 0 | clock phase |
| nssByteNotXfer | sl |  | 0 | set nss high in between bytes |
| misoPrecphaNotCpha | sl |  | 0 | set mosi a half clock ahead |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| req | in | std_logic | 1 |  |
| ack | out | std_logic | 1 |  |
| len | in | std_logic_vector | 32 |  |
| recvAXIS_tready | in | std_logic | 1 |  |
| recvAXIS_tvalid | out | std_logic | 1 |  |
| recvAXIS_tdata | out | std_logic_vector | 8 |  |
| recvAXIS_tlast | out | std_logic | 1 |  |
| sendAXIS_tready | out | std_logic | 1 |  |
| sendAXIS_tvalid | in | std_logic | 1 |  |
| sendAXIS_tdata | in | std_logic_vector | 8 |  |
| sendAXIS_tlast | in | std_logic | 1 |  |
| nss | in | std_logic | 1 |  |
| sclk | in | std_logic | 1 |  |
| mosi | in | std_logic | 1 |  |
| miso | inout | std_logic | 1 |  |

