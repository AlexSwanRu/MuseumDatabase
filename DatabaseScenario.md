# Сценарий использования базы данных
> Предложенная мною структура баы данных является концептуальной, составлена по результатам посещения "Алуштинского литературно-мемориального музея С.Н. Сергеева-Ценского", бесед с руоводителеи и коллективом Музея. и, естественно не подразумевает мгновенное использования в текущей структуре, но, после взаимных компромисных доработок логики связей и вида представоения таблиц, возможно тестовое внедрение.

## Назначение базы данных

Данная концепция базы данных расчитана на использование оргазициями, которые ведут выставочную деятельность: имеют собственную или привлекаемые коллекции экспонатов,  собственные или арендные места хранения (выстовочные залы).
Предназначена для учета экспонатов и аналитики посетителей. Прослеживает связи выставка -> экспонаты и экспонат -> положение экспоната.
Имеется возможность контролировать и отслеживать интернет ресурсы музея. Следить за своевременной реставрацией экспонатов и контролировать её своевременное проведение. Проводить простейщий скрининг доходов деятельности музея.

Данная база данных писалась на основе объекта: "Алуштинский литературно-мемориальный музей С.Н. Сергеева-Ценского". 
Адрес объекта :   г. Алушта, ул. С.Н.Сергеева-Ценского, 5


## Содержание сторонних баз данных

### Общероссийский классификатор организационно-правовых форм (ОКОПФ)

Используется для упрощения ведения таблицы "Организации" и исключения возможных ошибок при создании новых записей. Использование общероссийского классификатора способствует унификации данных и простоте взаимодействия с ними.


