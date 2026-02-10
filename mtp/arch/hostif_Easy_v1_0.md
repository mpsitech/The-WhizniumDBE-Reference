host interface (hostif_Easy_v1_0)
===

**Description**: universal PHY host interface

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| phytype | uart | axi/spi/uart |
| wA | 32 | address width for AXI [bit] |
| wD | 32 | data width 16/32/64/128 for AXI [bit] |
| fSclk | 115200 | baud rate for SPI/UART [bps] |


### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fSclk | nat |  | 115200 | baud rate |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| tkclk | in | sl | 1 |  |
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
| nss | in | sl | 1 |  |
| sclk | in | sl | 1 |  |
| mosi | in | sl | 1 |  |
| miso | inout | sl | 1 |  |
| rxd | in | sl | 1 |  |
| txd | out | sl | 1 |  |

