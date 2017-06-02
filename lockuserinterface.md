# lockuserinterface



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/lockuserinterface   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/lockuserinterface_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _false_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/lockuserinterface",
    "recordable": 0,
    "type": "stringValue",
    "value": "false",
    "writeable": 1
}
```
