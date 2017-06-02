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
| ------------- | :------: | :------------------------------ |
|  id | `/system/location/latitude` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `51.123456` | Location Latitude |
|  writeable | `1` | Writable parameter (0=No) |



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
