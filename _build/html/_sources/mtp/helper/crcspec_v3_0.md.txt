CRC calculator (crcspec_v3_0)
===

**Description**: crc

### Parameters

| Identifier | Default Value | Description |
|---|---|---|
| poly | 8005 |  |
| wD | 32 |  |
| leNotBe | true | endianness |


### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| initInvert | _bool |  | false |  |
| byteFlip | _bool |  | false |  |
| outFlip | _bool |  | false |  |
| outInvert | _bool |  | false |  |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| AXIS_tready | out | sl | 1 |  |
| AXIS_tvalid | in | sl | 1 |  |
| AXIS_tdata | in | slvdn | 32 |  |
| AXIS_tkeep | in | slvdn | 4 |  |
| AXIS_tlast | in | sl | 1 |  |
| crc | out | slvdn | 16 |  |
| validCrc | out | sl | 1 |  |

