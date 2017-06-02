# temperaturestep



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/temperaturestep   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/temperaturestep_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _0.5_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/temperaturestep",
    "recordable": 0,
    "type": "stringValue",
    "value": "0.5",
    "writeable": 1
}
```
