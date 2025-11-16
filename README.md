# 🚀 Como rodar o projeto

Siga os passos abaixo para configurar e iniciar o ambiente completo usando **Docker Compose**.

---

BACKEND

Crie o arquivo .env
Colar as seguintes variaveis:

API_PORT=3333<br>
DB_PORT=5432<br>
DB_USERNAME=cubos_user<br>
DB_PASSWORD=123456<br>
DB_NAME=cubos_db<br>

---

Relacionadas com AWS:<br>
AWS_BUCKET_NAME=<br>
AWS_BUCKET_REGION=sa-east-1<br>
AWS_ACCESS_KEY_ID=<br>
AWS_SECRET_ACCESS_KEY=<br>


execute no terminal:
```bash
yarn
docker compose up -d
yarn migration:run
yarn seed:run
```


FRONTEND<br>
yarn<br>
yarn dev<br>


