 Инструкция для работы с Git и удалёнными репозиториямиё

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)
Подготовили репозиторий
## Создание коммитов
*Перенесла инструкцию в свой файл*
### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
*Добавила git add .*
### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
*Посмотрела два комита , решила сделать еще один , для наглядности*
## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"
Добавим новую запись для примера

## Выделение текста

Можно сделать текст перечёркнутым с помощью двух символов (~~).
Например, вот так: ~~Правильная запись~~

Можно выделить текс полужирным с помощью двух символов (**) или (**_).
Например, вот так: **Текст** или вот так: **Текст**_.

Можно выделить текст жирным курсивом с помощью символов (**_).
Например, вот так: **Текст**_
 ## Работа с чужими версиями 

1.Сначала делаем (fork)интересующего нас репозитория
2. Мы делаем git clone для нашей версии этого репозитория
3. Появляется наша версия и ее кланируем
4. Создаем ветку с нашими изменениями
5. Прозиводим все изменения  только в нашей ветке
6. Отправляем все изменения в свой аккаунт (push)
7/ После жтого в окне GitHub появляется возмодность отправить pull request## Работа с чужими версиями 

1.Сначала делаем (fork)интересующего нас репозитория
2. Мы делаем git clone для нашей версии этого репозитория
3. Появляется наша версия и ее кланируем
4. Создаем ветку с нашими изменениями
5. Прозиводим все изменения  только в нашей ветке
6. Отправляем все изменения в свой аккаунт (push)
7/ После жтого в окне GitHub появляется возмодность отправить pull request
