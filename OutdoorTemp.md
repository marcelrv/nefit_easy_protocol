## Outdoor Temperature Message

Provides outdoor temperature information

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /system/sensors/temperatures/outdoor_t1   |
| Parameters  | N/A  |

### Example

> {"id":"/system/sensors/temperatures/outdoor_t1","type":"floatValue","recordable":0,"writeable":0,"value":19,"unitOfMeasure":"C","minValue":-25,"maxValue":50,"status":"ok","srcType":"physical"}


### Content

| Key  | Example | Description |
| ------------- | :------: | ------------- |
| id  | /system/sensors/temperatures/outdoor_t1  | Message ID  |
| type  | floatValue  | data type of value  |
| recordable  | 0  | Recordable parameter (0=No)  |
| writeable  | 0  | Writable parameter (0=No) |
| value  | 19  | Current Temperature  |
| unitOfMeasure | C |  unitOfMeasure  |
|minValue | -25 |  minimum value  |
|maxValue | 50 |  maximum value  |
|status | ok |    |
|srcType | physical | Physical or internet based temperature   |
