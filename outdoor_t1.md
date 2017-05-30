# Outdoor Temperature Message

Provides outdoor temperature information from physical sensor or internet

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/sensors/temperatures/outdoor_t1   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | /system/sensors/temperatures/outdoor_t1 | Message ID (URL) |
|  maxValue | 50 |  |
|  minValue | -25 |  |
|  recordable | 0 | Recordable parameter (0=No) |
|  srcType | physical |  |
|  status | ok |  |
|  type | floatValue | Data type of value |
|  unitOfMeasure | C |  |
|  value | 25 |  |
|  writeable | 0 | Writable parameter (0=No) |



### Example
```
{
    "id": "/system/sensors/temperatures/outdoor_t1",
    "maxValue": 50,
    "minValue": -25,
    "recordable": 0,
    "srcType": "physical",
    "status": "ok",
    "type": "floatValue",
    "unitOfMeasure": "C",
    "value": 25,
    "writeable": 0
}
```
