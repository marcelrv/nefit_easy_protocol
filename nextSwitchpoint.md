# nextSwitchpoint



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/selflearning/nextSwitchpoint   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/selflearning/nextSwitchpoint_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _switchpoint_ | Data type of value |
|  value | _{"t": 0, "T": 5, "d": "Su"}_ |  |
|  writeable | _1_ | Writable parameter (0=No) |


### switchpoint type details 

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  T | _5_ |  |
|  d | _Su_ |  |
|  t | _0_ |  |


### Example Message Content
```
{
    "id": "/ecus/rrc/selflearning/nextSwitchpoint",
    "recordable": 0,
    "type": "switchpoint",
    "value": {
        "T": 5,
        "d": "Su",
        "t": 0
    },
    "writeable": 1
}
```
