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
| ------------- | :------: | :------------------------------ |
|  id | `/ecus/rrc/recordings/yearTotal` | Message ID (URL) |
|  maxValue | `429496729.5` | Maximum allowed value |
|  minValue | `0` | Minimum allowed value |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `floatValue` | Data type of value |
|  unitOfMeasure | `kWh` | Unit of Measure |
|  value | `30.2` | YTD Usage |
|  writeable | `0` | Writable parameter (0=No) |



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
