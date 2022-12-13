# 3d_week_karpov.courses
Demo version of the course "Data Analyst" of the school karpov.courses 3d week HW and mini-project 2
# Проект визуализации данных
## Задачи
* Импортируйте библиотеку pandas как pd. Загрузите два датасета user_data и logs. Проверьте размер таблицы, типы переменных, наличие пропущенных значений, описательную статистику.
* Какой клиент совершил больше всего успешных операций? (success == True)
* С какой платформы осуществляется наибольшее количество успешных операций?
* Какую платформу предпочитают премиумные клиенты?
* Визуализируйте распределение возраста клиентов в зависимости от типа клиента (премиум или нет)
* Постройте график распределения числа успешных операций
*Визуализируйте число успешных операций, сделанных на платформе computer, в зависимости от возраста, используя sns.countplot (x – возраст, y – число успешных операций). Клиенты какого возраста совершили наибольшее количество успешных действий?
      
Описание данных

user_data:

* client – идентификатор пользователя
* premium – является ли клиент премиум
* age – возраст
* 
logs:

* client – идентификатор пользователя
* success – результат (успех - 1, нет - 0)
* platform – платформа
* time – время в формате Unix
