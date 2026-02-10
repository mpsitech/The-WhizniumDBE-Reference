AXI stream FIFO (axisfifo_v1_0)
===

**Description**: AXI stream single clock distributed memory FIFO preserving tlast

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| z | nat |  | 16 | FIFO depth |
| wD | nat |  | 32 |  |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| clear | in | std_logic | 1 |  |
| igrAXIS_tready | out | std_logic | 1 |  |
| igrAXIS_tvalid | in | std_logic | 1 |  |
| igrAXIS_tdata | in | std_logic_vector | wD |  |
| igrAXIS_tkeep | in | std_logic_vector | wD/8 |  |
| igrAXIS_tlast | in | std_logic | 1 |  |
| egrAXIS_tready | in | std_logic | 1 |  |
| egrAXIS_tvalid | out | std_logic | 1 |  |
| egrAXIS_tdata | out | std_logic_vector | wD |  |
| egrAXIS_tkeep | out | std_logic_vector | wD/8 |  |
| egrAXIS_tlast | out | std_logic | 1 |  |
| level | out | std_logic_vector | 8 |  |

