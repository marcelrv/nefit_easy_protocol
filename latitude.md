# Location Information - latitude

Provides the location of the thermostat for outside temperature data

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/location/latitude   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/system/location/latitude_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _51.123456_ | Location Latitude |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/location/latitude",
    "recordable": 0,
    "type": "stringValue",
    "value": "51.123456",
    "writeable": 1
}
```
