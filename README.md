



# Путь в Python!

Это обучающий проект-"конспект"  
Буду писать сюда все то что учил...


## Содержание:
1. [Poetry](#poetry)
2. [Git](#git)
3. [Гайд по md файлам](#гайд-по-md-файлам)


# Poetry

Создание нового проекта:

```bash
    poetry new <name_project>
```

Инициализация проекта:

```bash
    poetry init
```

Добавить зависимость:

```bash
    poetry add <namepa_module>
```

Удалить зависимость:

```bash
    poetry remove <namepa_module>
```

Обновление зависимостей:

```bash
    poetry update
```

Или если конкретно:

```bash
    poetry update <namepa_module>
```

Установить из lock-файла:<br>
создаст (или обновит) виртуальное окружение и снимок lock-файла

```bash
    poetry install    
```

# Git

## gh - какие-то вещи которые часто мне пригодятся по Git.

Как залогинется:

```bash
    gh auth login
```

По умолчанию он:

Спросит, на каком хосте (выберите GitHub.com).

Какой протокол (https).

Предложит авторизацию через браузер (рекомендуется) или через токен.

Если хочу сразу открыть браузер для OAuth можно указать:

```bash
    gh auth login --web
```

Убедится что я залогинен: <br>

```bash
     gh auth status
```

Создание удаленного репозитория:

```bash
    gh repo create learning_project `
    --source=. `
    --remote=origin `
    --public `
    --push `
    --confirm
```

*_Где:_*<br>
**learning_project** – имя будущего репозитория на GitHub (по умолчанию совпадает с именем папки).

**--source=.** – взять текущую папку как источник.

**--remote=origin** – добавить удалённый под именем origin.

**--public** – создать публичный репозиторий (или --private для приватного).

**--push** – сразу запушить вашу текущую ветку (main) в origin.

**--confirm** – пропустить интерактивные вопросы и сразу выполнить.
<br><br><br><br>
# ***Гайд по md файлам:***

# Заголовок уровня 1

## Заголовок уровня 2

### Заголовок уровня 3

#### Заголовок уровня 4

##### Заголовок уровня 5

###### Заголовок уровня 6

Курсив:

*курсив*
_курсив_  
Жирный

**жирный**     <br>
__жирный__     <br>
Жирный курсив <br>

***жирный+курсив***   <br>
___жирный+курсив___   <br>
Зачёркнутый

~~зачёркнутый~~         <br>
<u>Подчёркнутый</u>     <br>
Моноширинный (код) в строке<br>

`Блочный код`    <br>

```python
# пример кода Python
def foo():
    return "bar"
```

Инлайн ссылка:

[Python](https://www.python.org/)

Инлайн со «всплывающей» подсказкой (title):

[Python](https://www.python.org/ "Оф. Сайт Python")

Автоматическая ссылка

<https://www.python.org/>

Сокращённая ссылка (GitHub-специфично):  

[](https://www.python.org/)

Если нужно оформить изображение-ссылку, синтаксис схож:  

[![cat](https://www.google.com/imgres?q=cat%20google&imgurl=https%3A%2F%2Fwww.onegreenplanet.org%2Fwp-content%2Fuploads%2F2023%2F07%2Fshutterstock_2252711707-scaled.jpg&imgrefurl=https%3A%2F%2Fwww.onegreenplanet.org%2Fanimals%2Fcat-titan-athens-tourist-attraction-google-maps%2F&docid=m0F8xmCet7wxpM&tbnid=37_dwb1gC_m15M&vet=12ahUKEwi_trWciKuOAxXJwQIHHbqeM7gQM3oECCwQAA..i&w=1920&h=1280&hcb=2&ved=2ahUKEwi_trWciKuOAxXJwQIHHbqeM7gQM3oECCwQAA)](https://www.python.org/)

