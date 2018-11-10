# Get user by ID with valid token

## Preconditions
* [Login With Valid Credential](../common/login.md)

## GET /api/users/1

| Header | Value |
| - | - |
| Authorization | Bearer {token} |

## Expectation

Should be return data of user id 1

| Assert | Expected |
| - | - |
| StatusCode | 200 |
| data.id | 1 |
| data.firstName | FOO |
| data.lastName | Bar |




