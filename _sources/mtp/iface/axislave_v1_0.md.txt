AXI slave (axislave_v1_0)
===

**Description**: AXI lite slave with AXI stream interface

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |
| wA | nat |  | 32 | address width [bit] |
| wD | nat |  | 32 | data width 16/32/64/128 [bit] |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| req | in | std_logic | 1 |  |
| ack | out | std_logic | 1 |  |
| dne | out | std_logic | 1 |  |
| sendNotRecv | in | std_logic | 1 |  |
| len | in | std_logic_vector | 32 |  |
| recvAXIS_tready | in | std_logic | 1 |  |
| recvAXIS_tvalid | out | std_logic | 1 |  |
| recvAXIS_tdata | out | std_logic_vector | wD |  |
| recvAXIS_tlast | out | std_logic | 1 |  |
| sendAXIS_tready | out | std_logic | 1 |  |
| sendAXIS_tvalid | in | std_logic | 1 |  |
| sendAXIS_tdata | in | std_logic_vector | wD |  |
| sendAXIS_tlast | in | std_logic | 1 |  |
| AXIL_araddr | in | std_logic_vector | wA |  |
| AXIL_arprot | in | std_logic_vector | 3 |  |
| AXIL_arready | out | std_logic | 1 |  |
| AXIL_arvalid | in | std_logic | 1 |  |
| AXIL_rdata | out | std_logic_vector | wD |  |
| AXIL_rready | in | std_logic | 1 |  |
| AXIL_rresp | out | std_logic_vector | 2 |  |
| AXIL_rvalid | out | std_logic | 1 |  |
| AXIL_rlast | out | std_logic | 1 |  |
| AXIL_awaddr | in | std_logic_vector | wA |  |
| AXIL_awprot | in | std_logic_vector | 3 |  |
| AXIL_awready | out | std_logic | 1 |  |
| AXIL_awvalid | in | std_logic | 1 |  |
| AXIL_wdata | in | std_logic_vector | wD |  |
| AXIL_wready | out | std_logic | 1 |  |
| AXIL_wstrb | in | std_logic_vector | wD/8 |  |
| AXIL_wvalid | in | std_logic | 1 |  |
| AXIL_bready | in | std_logic | 1 |  |
| AXIL_bresp | out | std_logic_vector | 2 |  |
| AXIL_bvalid | out | std_logic | 1 |  |

