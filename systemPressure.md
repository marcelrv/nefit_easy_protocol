# System Pressure



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/systemPressure   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /system/appliance/systemPressure | Message ID (URL) |
|  maxValue | 25 | Maximum allowed value |
|  minValue | 0 | Minimum allowed value |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | bar | Unit of Measure |
|  value | 25.5 | Water Pressure |
|  writeable | 0 | Writable parameter (0=No) |



### Example
```
{
    "id": "/system/appliance/systemPressure",
    "maxValue": 25,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "bar",
    "value": 25.5,
    "writeable": 0
}
```
