# temperaturestep



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/temperaturestep   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/temperaturestep | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | 0.5 |  |
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/temperaturestep",
    "recordable": 0,
    "type": "stringValue",
    "value": "0.5",
    "writeable": 1
}
```
