# Вопросы с собеседований

## Linux

- Опишите процесс загрузки ПК
- Что такое OOM. Как OOM-killer решает - какие процессы убить?
- Что такое inode?
- Load Average - что это такое, как высчитывается?
- Что такое Linux signal? Для чего используются? Какие сигналы можно перехватить? Отличие SIGKILL от SIGTERM?
- Какие бывают состояния у процессов? Что такое зомби процесс? Как возникают зомби процессы? 
- В чем разница между системными вызывами exec и fork?
- При попытке отмонтировать каталог получаем ошибку что каталог занят, как найти PID ?
- Опишите сценарий, когда вы можете получить ошибку "filesystem is full", но 'df' показывает наличие свободного места.
- Расскажите о плюсах systemd
- Что такое LVM?
- В чём разница между yum и apt?
- У вас ext4, место на диске есть, но записать на него не выходит, в чем проблема?
- Как восстановить файл, который сейчас открыт приложением, но который удалили?


## Network

- Для чего нужны и используются vlan? Сколько vlan может быть? 
- Что происходит, когда вы в браузере набираете https://www.google.com?
- Что такое TCP keep-alive?
- Расскажите о TCP handshake
- Расскажите о RR в DNS
- Расскажите, чем отличается proxy от nat?
- Расскажите, что описывает модель OSI?


## DevOps

- DevOps и Agile. Что это такое и в чем разница?
- Что такое статическая и динамическая линковка файлов?
- В чем разница между виртуализацией и контейнеризацией?
- CI/CD - опишите pipeline для приложения x
- Расскажите о архитектуре K8s?
- Что такое IaC? в чем разница между Chef, Ansible, Terraform?
- Какие плюсы и минусы есть у Ansible?
- В чем отличие роли от playbook?
- Что такое идемпотентность?
- Что такое state-full и stateless?
- (Дан Dockerfile c кучей слоев) Как бы вы уменьшили размер образа?
- Что такое cgroups и namespaces?
- Что такое Jobs, runner, stages? 
- Что такое система контроля версий? 
- Что такое Terraform provider?
- Какие механизмы позволяют изолировать процессы внутри докер контейнера?
- Представим задачу, вам нужно прочистить все камины в Бруклине, с чего вы начнёте и сколько возьмёте за работу? (Правильного ответа нет, оценивается сам подход к ответу)

## Database 

- В чем отличие между SQL и No-SQL базами данных?
- Как правильно делать бекапы SQL баз данных?
- Как можно ускорить работу Postgres?
- Что такое нормализация?
- Расскажите что такое primary key и foreign key