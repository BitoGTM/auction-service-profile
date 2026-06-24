# auction-service-profile

View and update user profiles.

**Tech:** TypeScript · Express · MySQL · Sequelize · NATS Streaming

## Events Consumed
- `UserCreated`

## Environment Variables
| Variable | Description |
|---|---|
| `JWT_KEY` | JWT secret |
| `MYSQL_ROOT_PASSWORD` | MySQL root password |
| `PROFILE_MYSQL_URI` | MySQL connection URI |
| `NATS_URL` | NATS Streaming server URL |
| `NATS_CLUSTER_ID` | NATS cluster ID |
| `NATS_CLIENT_ID` | Unique client ID |

## Local Dev
See [auction-infra](../auction-infra/README.md).
