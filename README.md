# DC software

Based on docker compose, each compose is treated as a piece of software. A set of tools is provided to manage it

## link

[https://github.com/jawide/dc-backend](https://github.com/jawide/dc-backend)

[https://github.com/jawide/dc-frontend](https://github.com/jawide/dc-frontend)

[https://github.com/jawide/dc-admin](https://github.com/jawide/dc-admin)

[https://github.com/jawide/dc-cli](https://github.com/jawide/dc-cli)

[https://github.com/jawide/dc-dc](https://github.com/jawide/dc-dc)

## port

| name        | port |
| ----------- | ---- |
| dc-backend  | 5000 |
| dc-frontend | 5001 |
| dc-admin    | 5002 |
| dc-cli      |      |

## build all

```
git clone https://github.com/jawide/dc
git clone https://github.com/jawide/dc-backend
git clone https://github.com/jawide/dc-frontend
git clone https://github.com/jawide/dc-admin
cd dc
docker compose up -d
```
