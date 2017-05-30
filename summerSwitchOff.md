# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/summerSwitchOff   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
summerSwitchOff message
|  id | /ecus/rrc/weatherDependent/summerSwitchOff | Message ID (URL) |
summerSwitchOff message
|  maxValue | 30 |  |
summerSwitchOff message
|  minValue | 10 |  |
summerSwitchOff message
|  recordable | 0 | Recordable parameter (0=No) |
summerSwitchOff message
|  type | floatValue | Data type of value |
summerSwitchOff message
|  unitOfMeasure | C |  |
summerSwitchOff message
|  value | 16 |  |
summerSwitchOff message
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