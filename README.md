# semana-tech-go-react-server


Como executar o projeto

1 - Execute as migrations

tern migrate --migrations ./internal/store/pgstore/migrations --config ./internal/store/pgstore/migrations/tern.conf

2 - Execute as sqlqueries
sqlc generate -f ./internal/store/pgstore/sqlc.yaml