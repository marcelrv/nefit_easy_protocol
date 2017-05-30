# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/minSupply   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
minSupply message
|  id | /ecus/rrc/weatherDependent/minSupply | Message ID (URL) |
minSupply message
|  maxValue | 90 |  |
minSupply message
|  minValue | 10 |  |
minSupply message
|  recordable | 0 | Recordable parameter (0=No) |
minSupply message
|  type | floatValue | Data type of value |
minSupply message
|  unitOfMeasure | C |  |
minSupply message
|  value | 20 |  |
minSupply message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/weatherDependent/minSupply",
    "maxValue": 90,
    "minValue": 10,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 20,
    "writeable": 1
}
```
