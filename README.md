# Домашнее задание к занятию "`9.01-Обзор систем IT-мониторинга`" - `Корольков Денис`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Создайте виртуальную машину в Yandex Cloud Compute Cloud и с помощью Yandex Monitoring создайте дашборд, на котором будет видно загрузку процессора.
Приложите скриншот.`
`Ответ:`

```

Последовательность выполнения:

Заходим в свой аккаунт YandexCloud:  

[screen1](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen1.png)

Создаем новую виртуальную машину (сервис –Compute Cloud):

[screen2](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen2.png)

Выбираем подходящие настройки для нашей ВМ:

[screen3](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen3.png)

SSH ключ создаем, например, с помощью PuttyGen:

[screen4](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen4.png)

Теперь нам необходимо настроить дашборд. (выбираем сервис Yandex Monitoring  Дашборды  Создать дашборд  далее выбираем (например: график) и задаем параметры, по которым будем мониторить наш объект (ВМ).

[screen5](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen5.png)
[screen6](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen6.png)
[screen7](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen7.png)
[screen8](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen8.png)
[screen9](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen9.png)

Чтобы мы могли заходить на наш хост с консоли, нам нужно создать пароль для пользователя. Для этого сперва воспользуемся putty и сгенерированным раннее (puttygen) private key. Зайдем по ssh на наш хост и командой passwd зададим пользователю root пароль: 123456789. Готово.

[screen10](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen10.png)
[screen11](https://github.com/KorolkovDenis/Zabbix-dz1/blob/main/Screen/screen11.png)


```

---
## Дополнительные задания (со звездочкой*)

Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

### Задание 2*

`С помощью Yandex Monitoring сделайте 2 алерта на загрузку процессора: WARN и ALARM. Создайте уведомление по e-mail.
Приложите скриншот с уведомлением.`
<<<<<<< HEAD
`Ответ:`
=======

>>>>>>> 35677aacc51621f73854abaf22c14849cc1be355
1. [Дополнительное задание]()

## Ссылка на мою работу в Google:

[Моя работа по Zabbix]()
