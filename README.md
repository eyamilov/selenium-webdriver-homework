## Учебный проект для курса "Selenium WebDriver: полное руководство"

Автор — [Евгений Ямилов](mailto:evgeny@yamilov.com)

### Запуск учебного приложения

```shell
docker pull barancev/web-apps-for-courses
docker run -d --name webapps -p 80:80 --restart=always barancev/web-apps-for-courses
```

После запуска приложение доступно по адресу: http://localhost/litecart/

Админка: http://localhost/litecart/admin/ (admin/admin)

### Запуск тестов

`./gradlew clean test`
