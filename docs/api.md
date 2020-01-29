# API

When a member reports business closed, it can be tracked with ChamberForge.

## Reporting

You can get aggregate number of referrals, 1-to-1s, guests, and business closed for a group or organization.  This is helpful reporting.

```javascript
/api/v2/report/group/{group_id}/referrals/{start_date}/{end_date}
```
- **group_id**: ID of group
- **start_date**: Start date
- **end_date**: End date

Sample output
```json
[
   {
      "name":"ChamberForge Demo",
      "referrals":0
   },
   {
      "name":"Dimitry Jacquet",
      "referrals":0
   },
   {
      "name":"Hugo McDonald",
      "referrals":0
   },
   {
      "name":"John Smith",
      "referrals":0
   },
   {
      "name":"John Yu",
      "referrals":0
   },
   {
      "name":"Linda Graziano",
      "referrals":1
   },
   {
      "name":"Seong Bae",
      "referrals":5
   }
]
```