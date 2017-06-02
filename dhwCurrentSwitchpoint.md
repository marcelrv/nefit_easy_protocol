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
| ------------- | :------: | ------------------------------ |
|  id | _/dhwCircuits/dhwA/dhwCurrentSwitchpoint_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _DhwProgram_ | Data type of value |
|  value | _[{u'active': u'on', u'dhw': u'on', u'd': u'Mo', u't': 1020}]_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



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
