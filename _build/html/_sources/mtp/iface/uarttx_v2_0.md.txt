UART transmitter (uarttx_v2_0)
===

**Description**: UART transmitter with AXI stream interface

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |
| fSclk | nat |  | 115200 | baud rate |
| NStop | nat |  | 1 | stop bits |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| req | in | std_logic | 1 |  |
| ack | out | std_logic | 1 |  |
| dne | out | std_logic | 1 |  |
| len | in | std_logic_vector | 32 |  |
| AXIS_tready | out | std_logic | 1 |  |
| AXIS_tvalid | in | std_logic | 1 |  |
| AXIS_tdata | in | std_logic_vector | 8 |  |
| AXIS_tlast | in | std_logic | 1 |  |
| txd | out | std_logic | 1 |  |

