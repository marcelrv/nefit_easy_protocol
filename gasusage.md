# Gas Usage History

Gas Usage History. 

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/recordings/gasusage   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | page=PAGE# |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/recordings/gasusage | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | recordings | Data type of value |
|  value | [{u'ch': 0, u'T': 226, u'hw': 3.8, u'd': u'29-05-2017'}, {u'ch': 0, u'T': 211, u'hw': 7.2, u'd': u'30-05-2017'}, {u'ch': 6553.5, u'T': -1, u'hw': 6553.5, u'd': u'255-256-65535'}] | Gas Usage Records for each day formatted in JSON
 d=Date formatted as DD-MM-YYYY hw=Hot Water |
|  writeable | 0 | Writable parameter (0=No) |



### Example
```
{
    "id": "/ecus/rrc/recordings/gasusage",
    "recordable": 0,
    "type": "recordings",
    "value": [
        {
            "T": 226,
            "ch": 0,
            "d": "29-05-2017",
            "hw": 3.8
        },
        {
            "T": 211,
            "ch": 0,
            "d": "30-05-2017",
            "hw": 7.2
        },
        {
            "T": -1,
            "ch": 6553.5,
            "d": "255-256-65535",
            "hw": 6553.5
        }
    ],
    "writeable": 0
}
```
