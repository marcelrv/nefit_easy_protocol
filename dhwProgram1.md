# dhwProgram1



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /dhwCircuits/dhwA/dhwProgram1   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/dhwCircuits/dhwA/dhwProgram1` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `DhwProgram` | Data type of value |
|  value | `[{u'active': u'on', u'dhw': u'on', u'd': u'Su', u't': 480}, {u'active': u'on', u'dhw': u'off', u'd': u'Su', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Su', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Su', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Su', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Su', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'Mo', u't': 420}, {u'active': u'on', u'dhw': u'off', u'd': u'Mo', u't': 540}, {u'active': u'on', u'dhw': u'on', u'd': u'Mo', u't': 1020}, {u'active': u'on', u'dhw': u'off', u'd': u'Mo', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Mo', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Mo', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'Tu', u't': 420}, {u'active': u'on', u'dhw': u'off', u'd': u'Tu', u't': 540}, {u'active': u'on', u'dhw': u'on', u'd': u'Tu', u't': 1020}, {u'active': u'on', u'dhw': u'off', u'd': u'Tu', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Tu', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Tu', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'We', u't': 420}, {u'active': u'on', u'dhw': u'off', u'd': u'We', u't': 540}, {u'active': u'on', u'dhw': u'on', u'd': u'We', u't': 1020}, {u'active': u'on', u'dhw': u'off', u'd': u'We', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'We', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'We', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'Th', u't': 420}, {u'active': u'on', u'dhw': u'off', u'd': u'Th', u't': 540}, {u'active': u'on', u'dhw': u'on', u'd': u'Th', u't': 1020}, {u'active': u'on', u'dhw': u'off', u'd': u'Th', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Th', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Th', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'Fr', u't': 420}, {u'active': u'on', u'dhw': u'off', u'd': u'Fr', u't': 540}, {u'active': u'on', u'dhw': u'on', u'd': u'Fr', u't': 1020}, {u'active': u'on', u'dhw': u'off', u'd': u'Fr', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Fr', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Fr', u't': 0}, {u'active': u'on', u'dhw': u'on', u'd': u'Sa', u't': 480}, {u'active': u'on', u'dhw': u'off', u'd': u'Sa', u't': 1380}, {u'active': u'off', u'dhw': u'off', u'd': u'Sa', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Sa', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Sa', u't': 0}, {u'active': u'off', u'dhw': u'off', u'd': u'Sa', u't': 0}]` |  |
|  writeable | `1` | Writable parameter (0=No) |


### DhwProgram type details 

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  active | `on` |  |
|  dhw | `on` |  |
|  d | `Su` |  |
|  t | `480` |  |


### Example Message Content
```
{
    "id": "/dhwCircuits/dhwA/dhwProgram1",
    "recordable": 0,
    "type": "DhwProgram",
    "value": [
        {
            "active": "on",
            "d": "Su",
            "dhw": "on",
            "t": 480
        },
        {
            "active": "on",
            "d": "Su",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Su",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Su",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Su",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Su",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "Mo",
            "dhw": "on",
            "t": 420
        },
        {
            "active": "on",
            "d": "Mo",
            "dhw": "off",
            "t": 540
        },
        {
            "active": "on",
            "d": "Mo",
            "dhw": "on",
            "t": 1020
        },
        {
            "active": "on",
            "d": "Mo",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Mo",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Mo",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "Tu",
            "dhw": "on",
            "t": 420
        },
        {
            "active": "on",
            "d": "Tu",
            "dhw": "off",
            "t": 540
        },
        {
            "active": "on",
            "d": "Tu",
            "dhw": "on",
            "t": 1020
        },
        {
            "active": "on",
            "d": "Tu",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Tu",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Tu",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "We",
            "dhw": "on",
            "t": 420
        },
        {
            "active": "on",
            "d": "We",
            "dhw": "off",
            "t": 540
        },
        {
            "active": "on",
            "d": "We",
            "dhw": "on",
            "t": 1020
        },
        {
            "active": "on",
            "d": "We",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "We",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "We",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "Th",
            "dhw": "on",
            "t": 420
        },
        {
            "active": "on",
            "d": "Th",
            "dhw": "off",
            "t": 540
        },
        {
            "active": "on",
            "d": "Th",
            "dhw": "on",
            "t": 1020
        },
        {
            "active": "on",
            "d": "Th",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Th",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Th",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "Fr",
            "dhw": "on",
            "t": 420
        },
        {
            "active": "on",
            "d": "Fr",
            "dhw": "off",
            "t": 540
        },
        {
            "active": "on",
            "d": "Fr",
            "dhw": "on",
            "t": 1020
        },
        {
            "active": "on",
            "d": "Fr",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Fr",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Fr",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "on",
            "d": "Sa",
            "dhw": "on",
            "t": 480
        },
        {
            "active": "on",
            "d": "Sa",
            "dhw": "off",
            "t": 1380
        },
        {
            "active": "off",
            "d": "Sa",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Sa",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Sa",
            "dhw": "off",
            "t": 0
        },
        {
            "active": "off",
            "d": "Sa",
            "dhw": "off",
            "t": 0
        }
    ],
    "writeable": 1
}
```
