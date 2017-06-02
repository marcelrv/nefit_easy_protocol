# nextSwitchpointEndtime



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/selflearning/nextSwitchpointEndtime   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/selflearning/nextSwitchpointEndtime_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _switchpoint_ | Data type of value |
|  value | _{"t": 0, "T": 5, "d": "Su"}_ |  |
|  writeable | _0_ | Writable parameter (0=No) |


### switchpoint type details 

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  T | _5_ |  |
|  d | _Su_ |  |
|  t | _0_ |  |


### Example Message Content
```
{
    "id": "/ecus/rrc/selflearning/nextSwitchpointEndtime",
    "recordable": 0,
    "type": "switchpoint",
    "value": {
        "T": 5,
        "d": "Su",
        "t": 0
    },
    "writeable": 0
}
```
