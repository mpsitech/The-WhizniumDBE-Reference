UART controller (uart_Easy_v1_0)
===

**Description**: UART transceiver

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| fMclk | nat |  | 50000 | in kHz |
| fSclk | nat |  | 115200 | baud rate |
| toRx | nat |  |  | RX timeout in tkclk clocks |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | std_logic | 1 |  |
| mclk | in | std_logic | 1 |  |
| tkclk | in | std_logic | 1 |  |
| getTixVState | out | std_logic_vector | 8 |  |
| getRxleft | out | std_logic_vector | 8 |  |
| getLenRxdata | out | std_logic_vector | 8 |  |
| getRxdata | out | std_logic_vector | 256 |  |
| reqInvRx | in | std_logic | 1 |  |
| ackInvRx | out | std_logic | 1 |  |
| rxLen | in | std_logic_vector | 8 |  |
| reqInvTx | in | std_logic | 1 |  |
| ackInvTx | out | std_logic | 1 |  |
| txLenData | in | std_logic_vector | 8 |  |
| txData | in | std_logic_vector | 256 |  |
| reqInvTxrx | in | std_logic | 1 |  |
| ackInvTxrx | out | std_logic | 1 |  |
| txrxLenTxdata | in | std_logic_vector | 8 |  |
| txrxTxdata | in | std_logic_vector | 256 |  |
| txrxRxlen | in | std_logic_vector | 8 |  |
| rxd | in | std_logic | 1 |  |
| txd | out | std_logic | 1 |  |

