# Сборка
cd cmd/skill
go build -o skill

# Запуск
./skill                        
Running server on :8080

./skill -a :8081
Running server on :8081

RUN_ADDR=:8082 ./skill -a :8081
Running server on :8082