# LR6
Лабораторная работа №6

**Цель лабораторной работы:** изучение базовых возможностей системы
управления версиями, опыт работы с Git Api, опыт работы с локальным и
удаленным репозиторием.

**Ход работы:**
1. Создал аккаунт на сайте GitHub ([мой аккаунт](https://github.com/EgorPlehanov)).
2. Сделал копию в личное хранилище [от сюда](https://github.com/Kurtyanik/LR6/).
3. Установил Git [от сюда](https://git-scm.com).
4. После установки настроил клиент Git, введя имя пользователя (4918 Плеханов Е.С.) и email (egor.plekhanov00@mail.ru).
Использовал команды:<br>git config --global user.name "4917 Плеханов Е.С.";<br>git config --global user.email egor.plekhanov00@mail.ru.
5. Клонировал удаленный репозиторий на компьютер.<br>
Использовал команду:<br>git clone https://github.com/EgorPlehanov/LR6.git<br>
	![Рисунок 1](https://github.com/EgorPlehanov/LR6/blob/report/Screenshots/%D0%9F%D1%83%D0%BD%D0%BA%D1%82%D1%8B%204-5.png?raw=true "Демонстация выполнения пунктов 4 и 5")<br>
	Рисунок 1. Демонстация выполнения пунктов 4 и 5
6. Перешел в ветку branch1, добавил файл и отредактировал его (через интерфейс GitHub). Далее подтянул изменения в локальный репозиторий.<br>
Использовал команды cd LR6, чтобы зайти в локальный репозиторий, git checkout branch1, чтобы перейти в побочную ветку и подтянул изменения с помощью команды pit pull https://github.com/caVenikk/LR6.git<br>
	![Рисунок 2](https://github.com/EgorPlehanov/LR6/blob/report/Screenshots/%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%84%D0%B0%D0%B9%D0%BB%D0%B0%20new.txt.png?raw=true)<br>
	Рисунок 2. Добавление и редактирование файла<br>
	![Рисунок 3](https://github.com/EgorPlehanov/LR6/blob/report/Screenshots/%D0%9F%D1%83%D0%BD%D0%BA%D1%82%D1%8B%206.png?raw=true)<br>
	Рисунок 3. Переход во вторую ветку и подтягивание изменений<br>
  	
***Продолжаем работу локально***

7. Получил историю операций для каждой из веток.
	![Рисунок 4](https://github.com/EgorPlehanov/LR6/blob/report/Screenshots/%D0%9F%D1%83%D0%BD%D0%BA%D1%82%207.png)<br>
	Рисунок 4. История операций в веток branch1 и master<br>
8. То же самое
Использовал команду git log в каждой из веток.<br>
	![Рисунок 6](https://github.com/EgorPlehanov/LR6/blob/report/Screenshots/%D0%9F%D1%83%D0%BD%D0%BA%D1%82%208.png)<br>
	Рисунок 6. Последние действия.<br>
9. Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.
