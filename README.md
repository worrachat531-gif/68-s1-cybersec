# Cyber Security

## Information
- Worrachat Sriburin (FIW)
- 6602041610011
- s6602041610011@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running a Service
## Database
```sh
docker compose -f db.yaml up #monotoring
docker compose -f db.yaml up -d #background daemon
```
## Postgres admin
```sh
docker compose -f admin.yaml up #monotoring
docker compose -f admin.yaml up -d #background daemon
```

## Strapi Application
```sh
docker compose -f app.yaml up #monotoring
docker compose -f app.yaml up -d #background daemon
```
