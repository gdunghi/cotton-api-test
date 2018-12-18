# Get user by ID with invalid token

## GET /api/v1/users/1

| Header | Value |
| - | - |
| Authorization | Bearer xxxinvalidxxtoken |

## Expectation

User should be return.

| Assert | Expected |
| - | - |
| StatusCode | 401 |

