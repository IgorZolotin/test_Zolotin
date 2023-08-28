# Создание справки по системе контроля версий GIT


## Как начать?
**Чтобы начать работать с системой контроля версий GIT, необходимо выполнить следующую команду:**

```c#
git init
```

## Как добавить файл в отслеживание

**Чтобы добавить файл в отслеживание, используйте, команду:**

```cs
git add namefile
```

# Команда для получения информации от git о его текущем состоянии

``Наиболее часто используемая команда``

```
git status
```

# Команды для работы с коммитами

* Переход от одного коммита к другому git commit
* Вернуться к актуальному состоянию и продолжить работу git checkout master

# Отображение разницы между текущим файлом и закоммиченным файлом

```cs
git diff
```

# Вывести лоu 2 последних коммитов

```cs
git log
```
# Вывести полную историю коммитов

```cs
git reflog
```


# Создание руководства по языку разметки MarkDawn


## Создание заголовков




## Создание изображений

Тут нужно добавить изображение
и тут тоже
и тут


## Добавление исходного кода


В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```

Самое приятное, что в коде не нужно заменять угловые скобки `< >` и амперсанд `&` на их html-сущности.


## Добавление таблиц

### Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Можно управлять выравниванием столбцов при помощи двоеточия.

| Left-Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |     **$1600** |
| col 2 is      | centered        |         $12   |
| zebra stripes | are neat        |        ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.

