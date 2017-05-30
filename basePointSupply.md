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
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/weatherDependent/basePointSupply | Message ID (URL) |
|  maxValue | 90 |  |
|  minValue | 20 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C |  |
|  value | 20 |  |
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
