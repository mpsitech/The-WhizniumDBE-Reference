UART receiver (uartrx_v2_0)
===

**Description**: UART receiver with AXI stream interface

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |
| fSclk | nat |  | 115200 | baud rate |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| req | in | std_logic | 1 |  |
| ack | out | std_logic | 1 |  |
| dne | out | std_logic | 1 |  |
| len | in | std_logic_vector | 32 |  |
| AXIS_tready | in | std_logic | 1 |  |
| AXIS_tvalid | out | std_logic | 1 |  |
| AXIS_tdata | out | std_logic_vector | 8 |  |
| AXIS_tlast | out | std_logic | 1 |  |
| rxd | in | std_logic | 1 |  |
| burst | in | std_logic | 1 |  |

