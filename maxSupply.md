# maxSupply



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/weatherDependent/maxSupply   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/weatherDependent/maxSupply_ | Message ID (URL) |
|  maxValue | _90_ | Maximum allowed value |
|  minValue | _25_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _C_ | Unit of Measure |
|  value | _90_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/weatherDependent/maxSupply",
    "maxValue": 90,
    "minValue": 25,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 90,
    "writeable": 1
}
```
