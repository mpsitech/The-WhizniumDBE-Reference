DDR memory multiplexer (ddrmux_Easy_v1_0)
===

**Description**: DDR memory access multiplexer (cross-vendor)

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| phyNotAxi | false | interface level |
| wAPhy | 20 | PHY address width [bit] |
| wDPhy | 16 | PHY data width [bit] |
| memclk | memclk | memory clock (ex. memclk) |
| memclkIntNotExt | false | memory clock origin |
| ratioMemclk | 5.33 | memory clock ratio wrt. master clock (ex. 1.25) |
| wA | 32 | AXI address width [bit] |
| wAConst | 10 | constant portion of AXI address width [bit] |
| aConst | 0000000000 | constant portion of AXI address |
| wD | 128 | AXI data width 128/512 [bit] |
| NRd | 1 | number of read channels |
| flexNBeatRds | false | read channel flexible beats per burst |
| NBeatRd | 16 | number of beats per read burst |
| wDRds | 128 | read channel data widths <= wD [bit] |
| clkRds | memclk | read channel clocks |
| ratioClkRds | 1 | read channel clock ratios wrt. memory clock |
| NWr | 1.0 | number of write channels |
| flexNBeatWrs | false | write channel flexible beats per burst |
| NBeatWr | 16 | number of beats per read burst |
| wDWrs | 128 | write channel data widths <= wD [bit] |
| clkWrs | memclk | write channel clocks |
| ratioClkWrs | 1.0 | write channel clock ratios wrt. memory clock |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| resetMemclk | in | sl | 1 |  |
| memclk | in | sl | 1 |  |
| tkclk | in | sl | 1 |  |
| ddrAXI_arid | out | slvdn | 6 |  |
| ddrAXI_araddr | out | slvdn | 32 |  |
| ddrAXI_arburst | out | slvdn | 2 |  |
| ddrAXI_arcache | out | slvdn | 4 |  |
| ddrAXI_arlen | out | slvdn | 8 |  |
| ddrAXI_arlock | out | slvdn | 1 |  |
| ddrAXI_arprot | out | slvdn | 3 |  |
| ddrAXI_arqos | out | slvdn | 4 |  |
| ddrAXI_arready | in | sl | 1 |  |
| ddrAXI_arregion | out | slvdn | 4 |  |
| ddrAXI_arsize | out | slvdn | 3 |  |
| ddrAXI_arvalid | out | sl | 1 |  |
| ddrAXI_rid | in | slvdn | 6 |  |
| ddrAXI_rdata | in | slvdn | 128 |  |
| ddrAXI_rlast | in | sl | 1 |  |
| ddrAXI_rready | out | sl | 1 |  |
| ddrAXI_rresp | in | slvdn | 2 |  |
| ddrAXI_rvalid | in | sl | 1 |  |
| ddrAXI_awid | out | slvdn | 6 |  |
| ddrAXI_awaddr | out | slvdn | 32 |  |
| ddrAXI_awburst | out | slvdn | 2 |  |
| ddrAXI_awcache | out | slvdn | 4 |  |
| ddrAXI_awlen | out | slvdn | 8 |  |
| ddrAXI_awlock | out | slvdn | 1 |  |
| ddrAXI_awprot | out | slvdn | 3 |  |
| ddrAXI_awqos | out | slvdn | 4 |  |
| ddrAXI_awready | in | sl | 1 |  |
| ddrAXI_awregion | out | slvdn | 4 |  |
| ddrAXI_awsize | out | slvdn | 3 |  |
| ddrAXI_awvalid | out | sl | 1 |  |
| ddrAXI_wdata | out | slvdn | 128 |  |
| ddrAXI_wlast | out | sl | 1 |  |
| ddrAXI_wready | in | sl | 1 |  |
| ddrAXI_wstrb | out | slvdn | 16 |  |
| ddrAXI_wvalid | out | sl | 1 |  |
| ddrAXI_bid | in | slvdn | 6 |  |
| ddrAXI_bready | out | sl | 1 |  |
| ddrAXI_bresp | in | slvdn | 2 |  |
| ddrAXI_bvalid | in | sl | 1 |  |

