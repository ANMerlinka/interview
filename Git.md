# Git

1) Что такое Git?

Git — это система контроля версий, которая позволяет отслеживать любые изменения в файлах, сохранять их версии и быстро возвращаться к предыдущим состояниям кода.

2) Зачем нужен Git?

- Позволяет сохранять историю изменений и легко откатываться к предыдущим версиям
- Упрощает совместную работу над проектом, позволяя нескольким разработчикам работать параллельно
- Возможность создавать и управлять различными ветками для разных задач и фич

3) Сколько систем контроля версий существует? - много

4) Что делает команда git status?

Она позволяет проверить текущее состояние вашего репозитория и увидеть, какие изменения были сделаны, а также их текущее состояние.

5) Что такое commit? - единица состояния проекта в Git

6) Как создать ветку my_branch?

```
git checkout -b my_branch
```

7) Что сделает команда git branch без какого-либо ключа(параметра)?

Команда git branch без каких-либо ключей или параметров выполняет функцию отображения списка всех существующих веток в вашем Git-репозитории. Эта команда действует как «менеджер веток», предоставляя информацию о всех созданных и активных ветках.

8) Для чего нужен файл .gitignore?

Файл .gitignore — это текстовый файл, который используется в системе контроля версий Git для определения игнорируемых файлов и каталогов. Основная цель этого файла — исключить определённые элементы из отслеживания Git’ом. Это особенно полезно в проектах, где присутствует множество временных, производных или приватных файлов, которые не должны быть включены в репозиторий.

9) Чем директория с репозиторием отличается от любой другой? 

Директория с репозиторием Git отличается от обычной директории несколькими важными аспектами:
- Наличие скрытой папки .git
- Чтобы создать репозиторий, необходимо выполнить команду git init в пустой директории или клонировать существующий репозиторий с помощью команды git clone. Эти команды создают структуру репозитория и инициализируют его.

