# Outdoor Temperature Message

Provides outdoor temperature information from physical sensor or internet

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/sensors/temperatures/outdoor_t1   |
| Recordable   | 0   |
| Writable   | 0   |
| Parameters  | N/A  |

## Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------- |
outdoor_t1 message
|  id | /system/sensors/temperatures/outdoor_t1 | Message ID (URL) |
outdoor_t1 message
|  maxValue | 50 |  |
outdoor_t1 message
|  minValue | -25 |  |
outdoor_t1 message
|  recordable | 0 | Recordable parameter (0=No) |
outdoor_t1 message
|  srcType | physical |  |
outdoor_t1 message
|  status | ok |  |
outdoor_t1 message
|  type | floatValue | Data type of value |
outdoor_t1 message
|  unitOfMeasure | C |  |
outdoor_t1 message
|  value | 25 |  |
outdoor_t1 message
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
