Чтобы запустить данный проект у себя локально / To run this project locally:

1. Скачайте этот репозиторий с github / Download this repository from github
2. Создайте у себя локально в дириктории todo-app file .env, где будет находиться: **DB_PASSWORD=qwerty** / Create a file .env locally "todo-app", where **DB_PASSWORD=qwerty** will be located
3. После этого откройте cmd и пропишите: **docker-compose up --build todo-app** / After that, open cmd and write: **docker-compose up --build todo-app**
4. Откройте еще один терминал и пропишите миграции к бд: **migrate -path ./schema -database postgres://postgres:qwerty@localhost:5436/postgres?sslmode=disable up ** / Open another terminal and register migrations to the database: **migrate -path ./schema -database postgres://postgres:qwerty@localhost:5436/postgres?sslmode=disable up **

Поздравляю. Вы развернули этот API у себя локально! / Congratulations. You have deployed this API locally!

