# Пример простого docker-compose файла для сборки war артефакта. 
Файл hello.war собирается в первом docker контейнере на основе [проекта boxfuse](https://github.com/boxfuse/boxfuse-sample-java-war-hello), 
затем через volume он становится доступен второму контейнеру с tomcat9 на 80 порту.
Для запуска введите команду

**docker-compose up -d**

Посмотреть результат можно по ссылке: http://your-server-ip/hello/
