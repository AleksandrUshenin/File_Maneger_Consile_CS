![2022-11-25](https://user-images.githubusercontent.com/102482033/204035523-b24352cd-d9e3-407f-9e37-3afb8a03c70c.png)
Рукаводство к библиотеке.

	Вызов команд : 

	1. Реализовать интерфейс "IUserInterface".
	2. Передать этот класс в "FileManagerLogic".
	3. При вызове команды класс реализованный интерфес "IUserInterface" должен вернуть в методе "ReadKey"
		заполненый обьект "UserCommandInfo".
	4.В "UserCommandInfo" должно быть выбран тип команды из списка "DisplayKey" и заполнено поле "LineCommand".
		В "LineCommand" можно передать : путь, команда (при выборе "LineCommand" из списка "DisplayKey").

	Команды :
		"cd" - смена директории.
		"cp" - копирование файла/папки.
		"rm" - удаление, "rm -D"/"rm - D" удаление не пустой папки.
		"mkdir" - создание директррии.
		"touch" - создание файла.
		"length" - получение иформации.
		"getdrives" - получение списка доступных дисков.
