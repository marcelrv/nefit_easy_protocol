# nextSwitchpoint



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/selflearning/nextSwitchpoint   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/selflearning/nextSwitchpoint | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | switchpoint | Data type of value |
|  value | {u't': 0, u'T': 5, u'd': u'Su'} |  |
|  T | 5 |  |
|  d | Su |  |
|  t | 0 |  |
|  writeable | 1 | Writable parameter (0=No) |

### Example
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
