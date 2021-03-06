# dhwCurrentSwitchpoint



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/dhwCurrentSwitchpoint   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/dhwCircuits/dhwA/dhwCurrentSwitchpoint` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `DhwProgram` | Data type of value |
|  value | `[{u'active': u'on', u'dhw': u'on', u'd': u'Mo', u't': 1020}]` |  |
|  writeable | `0` | Writable parameter (0=No) |


### DhwProgram type details 

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  active | `on` |  |
|  dhw | `on` |  |
|  d | `Mo` |  |
|  t | `1020` |  |


### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/dhwCurrentSwitchpoint",
    "recordable": 0,
    "type": "DhwProgram",
    "value": [
        {
            "active": "on",
            "d": "Mo",
            "dhw": "on",
            "t": 1020
        }
    ],
    "writeable": 0
}
```
