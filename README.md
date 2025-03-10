# Немного о Git!

Git - **open source** программа от создателя [Linux](https://www.linux.com/) - Линуса Товальда. Git позволяет создавать локальные репозитории <b>
на своём компьютере

Git не имеет графического интерфейса, и работать с ним предстоит из терминала. Поначалу это может быть неудобно, но со временем всё получится

## Ключевые команды:
- `git init` - создать git репозиторий
- `git status` - показывает статус репозитория
- `git add` - подготовить файлы к сохранению (не сохраняет! Только готовит!)
	- `--all` - флаг, позволяющий выбрать все файлы в директории
- `git commit` - сделать коммит (сохраняет только то, что подготовил `git add`)
	- `-m` - флаг, добавляющий сообщение коммиту. Комментарий идёт после флага в кавычках ""
- `git log` - посмотреть историю коммитов
- `git remote add` - добавить удалённый репозиторий (remote - удалённый)
- `git remote`
	- `-v` - == `--verbose` - флаг, показывающий более подробную информацию
- `git push` - загрузить локальный репозиторий на GitHub
	- `$ git push -u origin master` - загрузка в первый раз для нового репозитория
- `git clone` - копировать репозиторий
---
P.S. Не совершай моих ошибок и сохраняй изменения в файле - например, через `Ctrl` + `S`