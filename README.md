# docker-postgres


## Versões


Postgres: usei a versão 11 (postgres:11-alpine)


pgAdmin: usei a versão 4 (dpage/pgadmin4)


## docker-compose


Crie o arquivo docker-compose.yml
Adicione o conteúdo do arquivo docker-compose.yml postado aqui nesse repositório


## RUM
No terminal linux (recomendo usar WSL2) digite: $docker-compose up

Obs. o docker-compose build não deve ser usado nesse caso, porque tanto o Postgres e o pgAdmin já estão compilados na Imagem que estou usando


## Acesso ao pgAdmin

Endereço: http://localhost:5050/browser

Username: postgres

Password: changeme
