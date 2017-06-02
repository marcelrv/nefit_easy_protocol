# Location information - longitude

Provides the location of the thermostat for outside temperature data

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/location/longitude   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | :------------------------------ |
|  id | `/system/location/longitude` | Message ID (URL) |
|  recordable | `0` | Recordable parameter (0=No) |
|  type | `stringValue` | Data type of value |
|  value | `4.1234567` | Location Longitude |
|  writeable | `1` | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/system/location/longitude",
    "recordable": 0,
    "type": "stringValue",
    "value": "4.1234567",
    "writeable": 1
}
```
