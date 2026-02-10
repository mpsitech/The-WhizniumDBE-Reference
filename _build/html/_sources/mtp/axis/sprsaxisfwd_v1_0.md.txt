sparse AXI stream forwarder (sprsaxisfwd_v1_0)
===

**Description**: unstable ingress sparse AXI stream forwarder with no back-pressure allowed

### Generics

| Identifier | Type | Width | Default | Description |
|---|---|---|---|---|
| wSize | nat |  |  | max. transaction size |
| wIxHshk | nat |  |  | _tvalid/_tlast register size |
| wIxData | nat |  |  | _tdata register size |
| wD | nat |  |  | data width |


### Ports

| Identifier | Direction | Type | Width | Comment |
|---|---|---|---|---|
| resetIgrclk | in | sl | 1 | in mclk domain |
| igrclk | in | sl | 1 |  |
| reset | in | sl | 1 |  |
| mclk | in | sl | 1 |  |
| igrAXIS_tready | out | sl | 1 | always 1 |
| igrAXIS_tvalid | in | sl | 1 |  |
| igrAXIS_tdata | in | slvdn | 1 |  |
| igrAXIS_tkeep | in | slvdn | 1 |  |
| igrAXIS_tlast | in | sl | 1 |  |
| egrAXIS_tready | in | sl | 1 | ignored |
| egrAXIS_tvalid | out | sl | 1 |  |
| egrAXIS_tdata | out | slvdn | 1 |  |
| egrAXIS_tkeep | out | slvdn | 1 |  |
| egrAXIS_tlast | out | sl | 1 |  |

