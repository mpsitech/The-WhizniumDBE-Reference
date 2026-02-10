memory-mapped AXI co-host interface (aximmcohostif_Easy_v1_0)
===

**Description**: memory-mapped AXI lite co-host interface

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| wA | 32 | address width [bit] |
| wD | 32 | data width 16/32/64/128 [bit] |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| commok | out | sl | 1 |  |
| reqReset | out | sl | 1 |  |
| AXIL_araddr | in | slvdn | 32 |  |
| AXIL_arprot | in | slvdn | 3 |  |
| AXIL_arready | out | sl | 1 |  |
| AXIL_arvalid | in | sl | 1 |  |
| AXIL_rdata | out | slvdn | 32 |  |
| AXIL_rready | in | sl | 1 |  |
| AXIL_rresp | out | slvdn | 2 |  |
| AXIL_rvalid | out | sl | 1 |  |
| AXIL_rlast | out | sl | 1 |  |
| AXIL_awaddr | in | slvdn | 32 |  |
| AXIL_awprot | in | slvdn | 3 |  |
| AXIL_awready | out | sl | 1 |  |
| AXIL_awvalid | in | sl | 1 |  |
| AXIL_wdata | in | slvdn | 32 |  |
| AXIL_wready | out | sl | 1 |  |
| AXIL_wstrb | in | slvdn | 4 |  |
| AXIL_wvalid | in | sl | 1 |  |
| AXIL_bready | in | sl | 1 |  |
| AXIL_bresp | out | slvdn | 2 |  |
| AXIL_bvalid | out | sl | 1 |  |

