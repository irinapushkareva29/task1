[<u>На главную</u>](./readme.md)

### Команды по отладке

В Git есть несколько команд, используемых для нахождения проблем в коде. Это команды для поиска места в истории, где проблема впервые проявилась и собственно виновника этой проблемы.

#### git bisect
Команда *git bisect* — это чрезвычайно полезная утилита для поиска коммита в котором впервые проявился баг или проблема с помощью автоматического бинарного поиска.

#### git blame
Команда *git blame* выводит перед каждой строкой файла SHA-1 коммита, последний раз менявшего эту строку и автора этого коммита. Это помогает в поисках человека, которому нужно задавать вопросы о проблемном куске кода.

#### git grep
Команда *git grep* используется для поиска любой строки или регулярного выражения в любом из файлов вашего проекта, даже в более ранних его версиях.