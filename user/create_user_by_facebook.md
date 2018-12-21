# Create user by facebook

## Preconditions
* [Remove fb user](../common/delete_fb_user.md)

## POST /api/v1/users/auth/facebook

| Header | Value |
| - | - |
| Content-Type | application/json |

```
{
    "firstName": "Cutton01",
    "lastName": "HOSP",
    "isActive": true,
    "gender": "M",
    "disease": "heartdisease",
    "birthDate": "2006-01-01T17:00:00.000Z",
    "email": "foo@odds.team",
    "mobileNo": "0123456789",
    "description": "description",
    "hospitalId": 1,
    "idNo": "01122321232",
    "imageUrl": "https://scontent.fbkk5-7.fna.fbcdn.net/v/t1.0-0/p206x206/43253536_10215177693269753_6197605832096481280_n.jpg?_nc_cat=107&_nc_ht=scontent.fbkk5-7.fna&oh=21c36033108481590fda250d82345fc5&oe=5C67FB29",
    "allergies": "",
    "citizenId":"1111111111119",
    "facebookId":"cutton_fb_01"
}
```

## Expectation
Should be return token

| Assert | Expected |
| - | - |
| StatusCode | 200 |




