[< к содержанию](./readme.md)

## git clone

**git clone** - используется для создания нового каталога, переходит внутрь и выполняет git init для создания пустого репозитория, затем она добавляет новый удалённый репозиторий (git remote add) для указанного URL (по умолчанию он получит имя origin), выполняет git fetch для этого репозитория и, наконец, извлекает последний коммит в ваш рабочий каталог, используя git checkout.

Чтобы создать копию репозитория, используйте команду:

```bash=
git clone .
```