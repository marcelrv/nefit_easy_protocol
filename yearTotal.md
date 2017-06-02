# Overall Gas Usage (YTD)

Provides the Gas Usage -Year To Date

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/recordings/yearTotal   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/recordings/yearTotal_ | Message ID (URL) |
|  maxValue | _429496729.5_ | Maximum allowed value |
|  minValue | _0_ | Minimum allowed value |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _floatValue_ | Data type of value |
|  unitOfMeasure | _kWh_ | Unit of Measure |
|  value | _30.2_ | YTD Usage |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/recordings/yearTotal",
    "maxValue": 429496729.5,
    "minValue": 0,
    "recordable": 0,
    "type": "floatValue",
    "unitOfMeasure": "kWh",
    "value": 30.2,
    "writeable": 0
}
```
