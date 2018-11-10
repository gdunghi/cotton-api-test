# Get user by id without token should be response 401

This can be run with `cotton -u https://localhost:8000/api/users get_user.md`

## GET /api/users/1

| Header | Value |
| - | - |
| Authorization | Bearer {token} |


Perform a get user by id `1`.

## Expectation

| Assert | Expected |
| - | - |
| StatusCode | 401 |