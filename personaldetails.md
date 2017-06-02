# personaldetails



### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/personaldetails   |
| Recordable   | False   |
| Writable   | True   |
| Parameters  | N/A |

### Detailed Content

|  Key  | Example | Description |
| ------------- | :------: | ------------------------------ |
|  id | _/ecus/rrc/personaldetails_ | Message ID (URL) |
|  recordable | _0_ | Recordable parameter (0=No) |
|  type | _stringValue_ | Data type of value |
|  value | _User Name;tel#;email@example.com_ |  |
|  writeable | _1_ | Writable parameter (0=No) |



### Example Message Content
```
{
    "id": "/ecus/rrc/personaldetails",
    "recordable": 0,
    "type": "stringValue",
    "value": "User Name;tel#;email@example.com",
    "writeable": 1
}
```
