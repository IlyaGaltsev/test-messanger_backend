### Развертывание на машине

создайте файлы .development.end и  .production.env (если их нет в корне), образец можно скопировать из .example.env 

далее перейти в терминал 

docker-compose build

docker-compose up -d

если ругается на bcrypt то нужно зайти в контейнер main и прописать в терминале
npm rebuild bcrypt --update-binary

### Задачи на доработку

[x] - Шифровать пароль
[ ] - Валидацию адекватную, библиотечную сделай
[ ] - Может структуру проекта поменять на entities , controllers , modules ... мб так удобнее будет указать путь до модулей в app.module
[ ] - ws добавь чтобы в realtime данные обновлялись
[ ] - добавь в sgitignore .development.env и .production.env файлы 
[ ] - в идеале пароль не должен отдаваться на фронт
[ ] -
[ ] -
[ ] -