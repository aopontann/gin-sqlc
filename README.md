### migration
```
export DATABASE_URL='postgres://postgres:password@localhost:5432/postgres?sslmode=disable'
migrate -database ${DATABASE_URL} -path db/migration up
```