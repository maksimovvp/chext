Расширения для Google Chrome.
Проверяет доступность сервисов
inlink,
allposition,
pars,

Состояние сервисов:
доступность,
результаты работы - журнал,

	работает ли сервис в данный момент,
	статистика работы:
		 - отчёты о работе,
		 - ...
	текущее состояние:
		 - запущены ли демоны,
		 - сколько проектов,
		 - ...

Request
Запрос:
cmd=''&
data=''&	//	необязательный параметр
key=''

Response
Ответ:
code:
status:
response:

Список команд:
 - получить полные сведения
	таблица
				параметр1|параметр2|параметр3|...|параметрm
		дата1	значение  значение  значение      значение
		дата2	значение  значение  значение      значение
		...		...
		датаn	значение  значение  значение      значение

		параметры означают работоспособность того или иного функционала

 - получить состояние
	доступность, работоспособность (выполнение всех функций)
	+, +
	+, -
	-, не активно