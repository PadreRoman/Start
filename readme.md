# Инструкция по работа GIT

LICENSE: [MIT](./license.md)

![](./assets/Git-logo.svg.png)
                                        
---

### Описание:

Git — это бесплатная распределенная система контроля версий с открытым исходным кодом, предназначенная для быстрой и эффективной обработки любых проектов, от небольших до очень крупных.


## Системы контроля версий:

• [Локальная](./local.md) - система хранит файлы на одном устройстве.

• [Централизованная](./central.md) - использует общий сервер.

• [Распределённая](./distributet.md) — общее облачное хранилище и локальные устройства участников команды. 

---

## Установка Git:

Прежде чем использовать Git, вы должны установить его на свой компьютер. Даже если он уже установлен, наверное, это хороший повод, чтобы обновиться до последней версии. Вы можете установить Git из собранного пакета или другого установщика, либо скачать исходный код и скомпилировать его самостоятельно. Есть три варианта установки:
1. [Установка в Linux](./install-Linux.md)
2. [Установка на Mac](./install-MacOC.md)
3. [Установка в Windows](./install-Windows.md)

## Создание Git-репозитория:

Создать репозитории Git можно одним из двух способов:

1. Вы можете взять локальный каталог, который в настоящее время не находится под версионным контролем, и превратить его в репозиторий Git.
2. Вы можете клонировать существующий репозиторий Git из любого места.

В обоих случаях вы сделаете готовый к работе Git репозиторий на вашем компьютере.



## Основные операции:

1. [git add](./add.md)
2. [git status](status.md)
3. [git diff](diff.md)
4. [git difftool](difftool.md)
5. [git commit](commit.md)
6. [git reset](reset.md)
7. [git rm](rm.md)
8. [git mv](mv.md)
9. [git clean](clean.md)
10. [git clone](./clone.md)

## Файл .gitignore:
Это обычный текстовый файл, который содержит список всех указанных файлов и папок проекта, которые Git должен игнорировать и не отслеживать.
Внутри файла .gitignore вы можете указать Git игнорировать только один файл или одну папку, указав имя или шаблон этого конкретного файла или папки. Используя такой же подход, вы можете указать Git игнорировать несколько файлов или папок.

[Правила синтаксиса файла .gitignore](./filesyntaxrules.md)

## Удаленный репозиторий:
Это репозиторий, хранящийся в облаке, на стороннем сервисе, специально созданном для работы с git имеет ряд преимуществ.

[Команды.](./remotecommands.md)

## Ветвление:
Это возможность работать над разными версиями проекта: вместо одного списка с упорядоченными коммитами история будет расходиться в определённых точках.

[Основы ветвления и слияния.](./branching.md)

[Команды.](./teams.md)

---

GIT logo by Jason Long. http://git-scm.com/downloads/logos, license: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)