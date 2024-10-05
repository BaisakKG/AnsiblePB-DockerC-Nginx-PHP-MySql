# AnsiblePB-DockerC-Nginx-PHP-MySql
Разработка Ansible Playbook для развертывания Dockerized веб-приложения

Как использовать:
  На стороне клиента: 
    - Нужен ansible для запуска playbook
    - Скачать файлы deploy-webapp-docker.yml и inventory
    - Настроить файл inventory (IP, ssh key...)

  На стороне сервера:
    - Almalinux 9
    
Если все ОК, в итоге по адресу IP:8080 будет запущен простой пример CRUD.