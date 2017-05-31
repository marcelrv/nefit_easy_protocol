# gasusagePointer



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/recordings/gasusagePointer   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /ecus/rrc/recordings/gasusagePointer | Message ID (URL) |
|  maxValue | 6400 | Maximum allowed value |
|  minValue | 1 | Minimum allowed value |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure |  | Unit of Measure |
|  value | 7 |  |
|  writeable | 0 | Writable parameter (0=No) |



### Example
```
{
    "id": "/ecus/rrc/recordings/gasusagePointer",
    "maxValue": 6400,
    "minValue": 1,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "",
    "value": 7,
    "writeable": 0
}
```
