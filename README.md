# Отчёт по лабораторной работе AWS

## 1. 
- ФИО: Кайнар Анна
- Группа: IA2403
- Выбранный уровень: Продвинутый

---

## 2. Задания базового уровня

Задание 1: бюджет ZeroSpend в списке Budgets.
![ZeroSpend Budget](images/budget.png)

Задание 2: экземпляр webserver в состоянии Running с пройденными проверками.
![EC2 Running](images/running.png)

Задание 3: страница nginx в браузере по публичному IP.
![Nginx Welcome Page](images/nginx.png)

Задание 4: вкладка Monitoring и фрагмент System log с установкой nginx.
![Monitoring and System Log](images/monitoring.png)
![Monitoring and System Log](images/systemlog.png)

Задание 5: успешное подключение по SSH и вывод systemctl status nginx.
![SSH Connection and Nginx Status](images/statusnginx.png)

Задание 6: ваш сайт в браузере и вывод ls -l /usr/share/nginx/html.
![Custom Website and Files List](images/site.png)
![Custom Website and Files List](images/index.png)

Задание 7: команда aws ec2 stop-instances и её вывод.
![AWS CLI Stop Instances](images/7.png)

---

## 3. Задания продвинутого уровня
![Задание 9](images/9.png)
Вход в базу по паролю: psql ... -c "SELECT 1;" возвращает 1.

![Задание 10](10.png)
Вывод php bin/init-db.php: Database is ready.

![Задание 11](11.1.png)
Вывод sudo nginx -t: syntax is ok, test is successful.

![Задание 11](11.png)
Приложение TimeCapsule в браузере по публичному IP.

![Задание 11](11.2.png)
Страница /health: {"status":"ok","db":"ok",...}.

![Задание 13](13.png)
Новая версия с моей надписью в подвале страницы.

![Задание 13](14.png)
Ошибка 500 после выпуска сломанной версии.

![Задание 13](14.1.png)
Работающий сайт после git revert и повторного деплоя.

## Архитектура

![Схема архитектуры](/arch.png)

Схема развёртывания TimeCapsule на одном экземпляре EC2.

ADR: [docs/adr/0001-deploy-method.md](docs/adr/0001-deploy-method.md)
