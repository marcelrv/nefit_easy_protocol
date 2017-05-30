# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/endPointSupply   |
| Recordable   | 0   |
| Writable   | 1   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
endPointSupply message
|  id | /ecus/rrc/weatherDependent/endPointSupply | Message ID (URL) |
endPointSupply message
|  maxValue | 90 |  |
endPointSupply message
|  minValue | 25 |  |
endPointSupply message
|  recordable | 0 | Recordable parameter (0=No) |
endPointSupply message
|  type | floatValue | Data type of value |
endPointSupply message
|  unitOfMeasure | C |  |
endPointSupply message
|  value | 75 |  |
endPointSupply message
|  writeable | 1 | Writable parameter (0=No) |

### Example
```
{
    "id": "/ecus/rrc/weatherDependent/endPointSupply",
    "maxValue": 90,
    "minValue": 25,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 75,
    "writeable": 1
}
```
