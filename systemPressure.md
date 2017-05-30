# 



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/appliance/systemPressure   |
| Recordable   | 0   |
| Writable   | 0   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
systemPressure message
|  id | /system/appliance/systemPressure | Message ID (URL) |
systemPressure message
|  maxValue | 25 |  |
systemPressure message
|  minValue | 0 |  |
systemPressure message
|  recordable | 0 | Recordable parameter (0=No) |
systemPressure message
|  type | floatValue | Data type of value |
systemPressure message
|  unitOfMeasure | bar |  |
systemPressure message
|  value | 25.5 |  |
systemPressure message
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
