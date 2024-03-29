# Работа c GIT!

## 1. Проверка наличия установленного Git
В терминале выполнить команду `"git --version"`
Если Git установлен, то появляется сообщение с информацией о версии программы. Иначе будет сообщение об ошибке.

## 2. Установка Git
Загружаем последнюю версию Git с сайта: https://git-scm.com/downloads

Устанавливаем с настройками по умолчанию


## 3. Настройка Git.
При первом использовании Git необходимо представиться. Для этого в терминале нужно ввести две команды:
```
git config --global user.name ""
git config -- global user.email
```
```Python
while (d < 2)
    d ++
```

## 4. Инициализация репозитория
После завершения настроек Git, необходимо инициализировать репозиторий при помощи команды:
```
git init
```
## 5. Содержание репозитория
Для проверки отсутствия или наличия коммитов необходимо ввести команду:
```
git status
```
## 6. Добавление файлов проекта в commit
```
git add . - добавление всех файлов
git add <имя файла> - добавление конкретного файла
```
## 7. Создание commit
Для создания commit необходимо ввести следующую команду:
```
1) git commit -m "Ввести необходимый комментарий"
2) git commit -a -m или git commit -am "Ввести необходимый комментарий"
```
Отличие первого commit от второго в том, что во втором случае, мы скомбинировали две команды git commit -m "" и git add

## 8. Просмотр журнала изменений
Если, Вам необходимо просмотреть журнал измненений нужно ввести следующую команду:
```
git log - вывод в терминале журнала со всеми данными
git log --oneline - более структурированный журнал с основными данными
git log --oneline -3 - выводит в терминале три первых изменения
git log --oneline -p - выводит в терминале журнал с разницей (аналогично git diff)
```
## 9. Выбор и переход к определенным изменениям файла
Для выбора и дальнейшейго перехода к определенным изменениям необходимо ввести команду:
```
git checkout <вставить код коммита, который получен при наборе комманды "git log">
```
Для того, чтобы перейти к актуальной версии файла, необходимо ввести команду в терминале:
```
git checkout master
или
git switch -
```