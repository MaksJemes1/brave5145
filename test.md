# Привет, Гитхаб
# Инструкция по работе с GIT
(# - заголовок 1 уровня или самый большой, ###### - заголовок 6 уровня, самый маленький)
## Основные команды Git
Чтобы создать новый репозиторий, использую команду:
* > **git init** - *создание нового репозитория, его инициализация*

Чтобы сохранить все файлы разом в репозитории, использую:
* > **git add .** - *добавить файл или файлы к следующему коммиту*

Чтобы узнать сохранены ли изменения использую: 
* > **git status** – *получить информацию от git о его текущем состоянии*

Чтобы указать изменения в данном сохранении использую:
* > **git commit -m “message”** - *cоздание коммита.*

Чтобы посмотреть историю сохранений использую:
* > **git log** - *вывод на экран истории всех коммитов с их хеш-кодами*

Чтобы перейти к другому сохранению использую:
* > **git checkout** - *переход от одного коммита к другому*

Чтобы вернуться к актуальному сохранению использую:
* > **git checkout master** - *вернуться к актуальному состоянию и продолжить работу*

Чтобы увидеть разницу между актуальной и сохраненной версией использую:
* > **git diff** - *увидеть разницу между текущим файлом и закоммиченным файлом*\

Чтобы посмотреть список веток использую: 
* > **git branch** – *посмотреть список веток в репозитории*

Чтобы создать ветку использую:
* > **git branch <название ветки>** – *создать новую ветку*

Чтбы переключиться на другую ветку использую:
* > **git checkout <название ветки>** – переход к другой ветке

Чтобы удалять ветки использую:
* > **git branch -d <название ветки>** – *удалить ветку*

Чтобы удалить ветку без проверки использую:
* > **git branch -D test** - *удаление без проверки на мердж*

Чтобы сразу создать и удалить ветку использую:
* > **git checkout -b test** - *переход и создание ветки одной командой*

Чтобы отправить изменения в Гитхаб, использую команду:
* > **git push** - *отправка изменений на удаленный репозиторий* 

Чтобы скопировать репозиторй с Гитхаба использую:
* > **git clone** - *копирует существующий репозиторий Git*

Чтобы обновить локальный репозиторий с GitHub использую:
* > **git pull** - *для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым.*