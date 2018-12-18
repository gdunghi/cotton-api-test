# Get user by id without token should be response 401

This can be run with `cotton -u http://hosp.odds.team:6969/api/v1/users get_user_empty_tokeng.md`

## GET /api/v1/users/1

| Header | Value |
| - | - |
| Authorization | Bearer {token} |


Perform a get user by id `1`.

## Expectation

| Assert | Expected |
| - | - |
| StatusCode | 401 |