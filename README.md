# Домашнее задание к занятию «Подъём инфраструктуры в Yandex Cloud»
Оформление домашнего задания
Домашнее задание выполните в Google Docs и отправьте на проверку ссылку на ваш документ в личном кабинете.
В названии файла укажите номер лекции и фамилию студента. Пример названия: 7.3. Подъём инфраструктуры в Yandex Cloud — Александр Александров.
Перед отправкой проверьте, что доступ для просмотра открыт всем, у кого есть ссылка. Если нужно прикрепить дополнительные ссылки, добавьте их в свой Google Docs.
Вы можете прислать решение в виде ссылки на ваш репозийторий в GitHub, для этого воспользуйтесь шаблоном для домашнего задания.

Важно
Перед началом работы над дипломным заданием изучите Инструкция по экономии облачных ресурсов.

## Задание 1
Выполните действия, приложите скриншот скриптов, скриншот выполненного проекта.

От заказчика получено задание: при помощи Terraform и Ansible собрать виртуальную инфраструктуру и развернуть на ней веб-ресурс.

В инфраструктуре нужна одна машина с ПО ОС Linux, двумя ядрами и двумя гигабайтами оперативной памяти.

Требуется установить nginx, залить при помощи Ansible конфигурационные файлы nginx и веб-ресурса.

**Скрины выполнения задания:**

[ссылка на конфиг terraform](https://github.com/anirisam1/terraform/blob/main/terra_configs)

![terraform.png](https://github.com/anirisam1/terraform/blob/main/img/terraform.png)
![terraform2.png](https://github.com/anirisam1/terraform/blob/main/img/terraform2.png)
![terraform3.png](https://github.com/anirisam1/terraform/blob/main/img/terraform3.png)
![terraform4.png](https://github.com/anirisam1/terraform/blob/main/img/terraform4.png)
![terraform5.png](https://github.com/anirisam1/terraform/blob/main/img/terraform5.png)
![terraform6.png](https://github.com/anirisam1/terraform/blob/main/img/terraform6.png)
![terraform_yc_vm.png](https://github.com/anirisam1/terraform/blob/main/img/terraform_yc_vm.png)
![terraform_ansible.png](https://github.com/anirisam1/terraform/blob/main/img/terraform_ansible.png)
![terraform_nginx.png](https://github.com/anirisam1/terraform/blob/main/img/terraform_nginx.png)

[ссылка на плейбук](https://github.com/anirisam1/terraform/blob/main/playbooks/terra.yml)

[ссылка на роль](https://github.com/anirisam1/terraform/tree/main/roles/terraform_test)
