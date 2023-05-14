### migration
```
export POSTGRESQL_URL='postgres://postgres:password@localhost:5432/postgres?sslmode=disable'
migrate -database ${POSTGRESQL_URL} -path db/migration up
```