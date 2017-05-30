# nightSwitchOff



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/nightSwitchOff   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/weatherDependent/nightSwitchOff | Message ID (URL) |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | stringValue | Data type of value |
|  value | keep on heating |  |
|  writeable | 1 | Writable parameter (0=No) |



### Example
```
{
    "id": "/ecus/rrc/weatherDependent/nightSwitchOff",
    "recordable": 0,
    "type": "stringValue",
    "value": "keep on heating",
    "writeable": 1
}
```
