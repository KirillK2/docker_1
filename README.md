Docker_1

1. выгрузить файлы из репозитория: Dockerfile, index.html.

2. собрать образ: docker build -t devops_course_nginx_up.

3. запустить контейнер: docker run -it --rm -d -p 80:80 devops_course_nginx_up.

4. проверить в браузере: http://127.0.0.1/ или http://localhost или из консоли: curl localhost:80.

6. остановить контейнер: docker stop devops_course_nginx_up.

7. удалить образ: docker image rm devops_course_nginx_up.