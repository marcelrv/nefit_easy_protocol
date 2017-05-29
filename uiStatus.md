
## Status Message

Provides status information

### Endpoint

| Info  | Details |
| ------------- | ------------- |
| URL   | /ecus/rrc/uiStatus   |
| Parameters  | N/A  |

### Example

> {"id":"/ecus/rrc/uiStatus","type":"uiUpdate","recordable":0,"writeable":0,"value":{"CTD":"2017-05-24T15:42:35+01:00We","CTR":"room","UMD":"clock","MMT":"15.0","CPM":"auto","CSP":"19","TOR":"off","TOD":"0","TOT":"21.0","TSP":"17.0","IHT":"25.00","IHS":"ok","DAS":"off","TAS":"off","HMD":"off","ARS":"init","FPA":"off","ESI":"off","BAI":"No","BLE":"false","BBE":"false","BMR":"false","PMR":"false","RS":"off","DHW":"on","HED_EN":"false","HED_DEV":"false","FAH":"false","DOT":"false","HED_DB":""}}


### Content

| Key  | Example | Description |
| ------------- | :------: | ------------- |
| id  | /ecus/rrc/uiStatus  | Message ID  |
| type  | uiUpdate  | data type of value  |
| recordable  | 0  | Recordable parameter (0=No)  |
| writeable  | 0  | Writable parameter (0=No) |
| value  |   | uiStatus record  |
| CTD | 2017-05-24T15:42:35+01:00We |    |
|CTR | room |    |
|UMD | clock |    |
|MMT | 15.0 |    |
|CPM | auto |    |
|CSP | 19 |    |
|TOR | off |    |
|TOD | 0 |    |
|TOT | 21.0 |    |
|TSP | 17.0 |    |
|IHT | 25.00 |    |
|IHS | ok |    |
|DAS | off |    |
|TAS | off |    |
|HMD | off |    |
|ARS | init |    |
|FPA | off |    |
|ESI | off |    |
|BAI | No |    |
|BLE | false |    |
|BBE | false |    |
|BMR | false |    |
|PMR | false |    |
|RS | off |    |
|DHW | on |    |
|HED_EN | false |    |
|HED_DEV | false |    |
|FAH | false |    |
|DOT | false |    |
|HED_DB |   |    |


