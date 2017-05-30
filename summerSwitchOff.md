# summerSwitchOff



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/summerSwitchOff   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/weatherDependent/summerSwitchOff | Message ID (URL) |
|  maxValue | 30 |  |
|  minValue | 10 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C |  |
|  value | 16 |  |
|  writeable | 1 | Writable parameter (0=No) |



### Example
```
{
    "id": "/ecus/rrc/weatherDependent/summerSwitchOff",
    "maxValue": 30,
    "minValue": 10,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 16,
    "writeable": 1
}
```
