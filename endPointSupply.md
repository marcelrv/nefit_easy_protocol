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
|  id | _/ecus/rrc/weatherDependent/endPointSupply_ | Message ID (URL) |
|  maxValue | _90_ | Maximum allowed value |
|  minValue | _25_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _75_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
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
