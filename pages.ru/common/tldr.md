# tldr

> Показывает простые страницы помощи для инструментов коммандной строки из проекта tldr-pages.
> Больше информации: <https://github.com/tldr-pages/tldr/blob/main/CLIENT-SPECIFICATION.md#command-line-interface>.

- Показывает типичное использование комманды (подсказка: то как вы попали сюда!):

`tldr {{команда}}`

- Показывает tldr страницу для комманды tar для Linux:

`tldr {{[-p|--platform]}} {{linux}} {{tar}}`

- Получить помощь по подкоманде Git:

`tldr {{git-checkout}}`

- Обновить локальные tldr страницы (если клиент поддерживает кэширование):

`tldr {{[-u|--update]}}`
