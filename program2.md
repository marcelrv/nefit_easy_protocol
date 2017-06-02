# program2



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/program2   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/userprogram/program2` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `UserProgram` | Data type of value |
|  value | `[{u'active': u'on', u't': 480, u'T': 20, u'name': 1, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}]` |  |
|  writeable | `1` | Writable parameter (0=No) |


### UserProgram type details 

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  active | `on` |  |
|  t | `480` |  |
|  T | `20` |  |
|  name | `1` |  |
|  d | `Su` |  |


### Example Message Content
```
{
    "id": "/ecus/rrc/userprogram/program2",
    "recordable": 0,
    "type": "UserProgram",
    "value": [
        {
            "T": 20,
            "active": "on",
            "d": "Su",
            "name": 1,
            "t": 480
        },
        {
            "T": 5,
            "active": "off",
            "d": "Su",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Su",
            "name": 0,
            "t": 0
        },
        {
            "T": 15,
            "active": "on",
            "d": "Su",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Su",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Su",
            "name": 0,
            "t": 0
        }
    ],
    "writeable": 1
}
```
