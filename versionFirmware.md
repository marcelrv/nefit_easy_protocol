# versionFirmware



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /gateway/versionFirmware   |
| Recordable   | False   |
| Writable   | False   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/gateway/versionFirmware_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _02.18.02_ |  |
|  writeable | _0_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/gateway/versionFirmware",
    "recordable": 0,
    "type": "stringValue",
    "value": "02.18.02",
    "writeable": 0
}
```
