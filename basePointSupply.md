# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/basePointSupply   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
basePointSupply message
|  id | /ecus/rrc/weatherDependent/basePointSupply | Message ID (URL) |
basePointSupply message
|  maxValue | 90 |  |
basePointSupply message
|  minValue | 20 |  |
basePointSupply message
|  recordable | 0 | Recordable parameter (0=No) |
basePointSupply message
|  type | floatValue | Data type of value |
basePointSupply message
|  unitOfMeasure | C |  |
basePointSupply message
|  value | 20 |  |
basePointSupply message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/weatherDependent/basePointSupply",
    "maxValue": 90,
    "minValue": 20,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 20,
    "writeable": 1
}
```
