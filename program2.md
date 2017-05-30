# program2



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/userprogram/program2   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/userprogram/program2 | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | UserProgram | Data type of value |
|  value | [{u'active': u'on', u't': 480, u'T': 20, u'name': 1, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Su'}, {u'active': u'on', u't': 420, u'T': 19, u'name': 1, u'd': u'Mo'}, {u'active': u'on', u't': 540, u'T': 17, u'name': 2, u'd': u'Mo'}, {u'active': u'on', u't': 1020, u'T': 20, u'name': 3, u'd': u'Mo'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Mo'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Mo'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Mo'}, {u'active': u'on', u't': 420, u'T': 19, u'name': 1, u'd': u'Tu'}, {u'active': u'on', u't': 540, u'T': 17, u'name': 2, u'd': u'Tu'}, {u'active': u'on', u't': 1020, u'T': 20, u'name': 3, u'd': u'Tu'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Tu'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Tu'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Tu'}, {u'active': u'on', u't': 420, u'T': 19, u'name': 1, u'd': u'We'}, {u'active': u'on', u't': 540, u'T': 17, u'name': 2, u'd': u'We'}, {u'active': u'on', u't': 1020, u'T': 20, u'name': 3, u'd': u'We'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'We'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'We'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'We'}, {u'active': u'on', u't': 420, u'T': 19, u'name': 1, u'd': u'Th'}, {u'active': u'on', u't': 540, u'T': 17, u'name': 2, u'd': u'Th'}, {u'active': u'on', u't': 1020, u'T': 20, u'name': 3, u'd': u'Th'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Th'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Th'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Th'}, {u'active': u'on', u't': 420, u'T': 19, u'name': 1, u'd': u'Fr'}, {u'active': u'on', u't': 540, u'T': 17, u'name': 2, u'd': u'Fr'}, {u'active': u'on', u't': 1020, u'T': 20, u'name': 3, u'd': u'Fr'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Fr'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Fr'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Fr'}, {u'active': u'on', u't': 480, u'T': 20, u'name': 1, u'd': u'Sa'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Sa'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Sa'}, {u'active': u'on', u't': 1380, u'T': 15, u'name': 0, u'd': u'Sa'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Sa'}, {u'active': u'off', u't': 0, u'T': 5, u'name': 0, u'd': u'Sa'}] |  |
|  writeable | 1 | Writable parameter (0=No) |



### Example
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
        },
        {
            "T": 19,
            "active": "on",
            "d": "Mo",
            "name": 1,
            "t": 420
        },
        {
            "T": 17,
            "active": "on",
            "d": "Mo",
            "name": 2,
            "t": 540
        },
        {
            "T": 20,
            "active": "on",
            "d": "Mo",
            "name": 3,
            "t": 1020
        },
        {
            "T": 15,
            "active": "on",
            "d": "Mo",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Mo",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Mo",
            "name": 0,
            "t": 0
        },
        {
            "T": 19,
            "active": "on",
            "d": "Tu",
            "name": 1,
            "t": 420
        },
        {
            "T": 17,
            "active": "on",
            "d": "Tu",
            "name": 2,
            "t": 540
        },
        {
            "T": 20,
            "active": "on",
            "d": "Tu",
            "name": 3,
            "t": 1020
        },
        {
            "T": 15,
            "active": "on",
            "d": "Tu",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Tu",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Tu",
            "name": 0,
            "t": 0
        },
        {
            "T": 19,
            "active": "on",
            "d": "We",
            "name": 1,
            "t": 420
        },
        {
            "T": 17,
            "active": "on",
            "d": "We",
            "name": 2,
            "t": 540
        },
        {
            "T": 20,
            "active": "on",
            "d": "We",
            "name": 3,
            "t": 1020
        },
        {
            "T": 15,
            "active": "on",
            "d": "We",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "We",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "We",
            "name": 0,
            "t": 0
        },
        {
            "T": 19,
            "active": "on",
            "d": "Th",
            "name": 1,
            "t": 420
        },
        {
            "T": 17,
            "active": "on",
            "d": "Th",
            "name": 2,
            "t": 540
        },
        {
            "T": 20,
            "active": "on",
            "d": "Th",
            "name": 3,
            "t": 1020
        },
        {
            "T": 15,
            "active": "on",
            "d": "Th",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Th",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Th",
            "name": 0,
            "t": 0
        },
        {
            "T": 19,
            "active": "on",
            "d": "Fr",
            "name": 1,
            "t": 420
        },
        {
            "T": 17,
            "active": "on",
            "d": "Fr",
            "name": 2,
            "t": 540
        },
        {
            "T": 20,
            "active": "on",
            "d": "Fr",
            "name": 3,
            "t": 1020
        },
        {
            "T": 15,
            "active": "on",
            "d": "Fr",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Fr",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Fr",
            "name": 0,
            "t": 0
        },
        {
            "T": 20,
            "active": "on",
            "d": "Sa",
            "name": 1,
            "t": 480
        },
        {
            "T": 5,
            "active": "off",
            "d": "Sa",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Sa",
            "name": 0,
            "t": 0
        },
        {
            "T": 15,
            "active": "on",
            "d": "Sa",
            "name": 0,
            "t": 1380
        },
        {
            "T": 5,
            "active": "off",
            "d": "Sa",
            "name": 0,
            "t": 0
        },
        {
            "T": 5,
            "active": "off",
            "d": "Sa",
            "name": 0,
            "t": 0
        }
    ],
    "writeable": 1
}
```
