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
| ------------- | :------: | ------------------------------ |
|  id | _/system/location/longitude_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _4.1234567_ | Location Longitude |
|  writeable | _1_ | Writable parameter (0=No) |



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
