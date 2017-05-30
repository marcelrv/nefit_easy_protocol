# endPointSupply



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/endPointSupply   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/weatherDependent/endPointSupply | Message ID (URL) |
|  maxValue | 90 |  |
|  minValue | 25 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C |  |
|  value | 75 |  |
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
