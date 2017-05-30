# systemPressure



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/systemPressure   |
| Recordable   | 0   |
| Writable   | 0   |
| Parameters  | N/A  |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /system/appliance/systemPressure | Message ID (URL) |
|  maxValue | 25 |  |
|  minValue | 0 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  type | floatValue | Data type of value |
|  unitOfMeasure | bar |  |
|  value | 25.5 |  |
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
