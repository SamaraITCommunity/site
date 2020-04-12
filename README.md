![CI](https://github.com/SamaraITCommunity/site/workflows/CI/badge.svg)

# Официальный сайт Samara IT Community

Репозиторий содержит исходный код для официального [сайта](https://sitc.community) Samara IT Community.
Если ты заметил ошибку или неточность, можешь создать issue или прислать pull request.

## Contribution Guide

### Initial Configuration

Дорогой друг - если ты решил помочь проекту и поработать над сайтом, то для начала стоит настроить окружение.
SITC.community является статическим сайтом, для генерации используется [Zola SSG](https://www.getzola.org) (ранее Gutenberg).
Почему именно этот генератор статических сайтов? -Потому что у @humb1t Rust головного мозга- Потому что так надо.

- Для установки Zola потребуется: скачать бинарник или воспользоваться пакетным менеджером [тут всё написано](https://www.getzola.org/documentation/getting-started/installation/).
- Далее качай наш репозиторий к себе на машину: <code>git clone https://github.com/SamaraITCommunity/site.git</code>
- Инициализировать конфигурационный файл на локальной машине: <code>git submodule init</code>
- Получить данные из всех подмодулей: <code>git submodule update</code>
- Ну и проверь что всё работает: <code>zola build</code>

### Getting Started

Чтобы лучше понять структуру нашего проекта - прочитай [немного документации по Zola структуре директорий](https://www.getzola.org/documentation/getting-started/directory-structure/). Затем походи по разделам - что это за файлики типа md? Не надо стесняться - иди с [markdown](https://daringfireball.net/projects/markdown/) ознакомляться. Все наши странички пишутся не на html, а на markdown - это нужно, чтобы не загромождать содержательную часть структурными элементами, не рассориться из-за стиля написания и дать возможность contribute всем участникам сообщества (даже ~~глупым~~ не знающим разметки бэкендщикам) ;-)
Окей - как всё это работает?
Запускаем команду <code>zola serve</code> и идём в браузер по адресу [127.0.0.1:1111](http://127.0.0.1:1111/) - вуаля, сайт должен быть тут. Если что-то пошло не так - обращайся в [наш ламповый телеграм чатик](https://t.me/samara_it) - там ~~тебя вылечат~~ тебе помогут.

### Push changes

Всю работу веди в отдельной веточке с говорящим названием - например <code>new-grindconf-info</code> или <code>grammatic-fixes</code>, старайся делать законченные, но небольшие изменения, которые логически связанны между собой в отдельных ветках. После того как ты сделаешь изменения - пожалуйста запусти <code>zola build</code> и проверь что все они собираются, а ещё лучше запусть <code>zola serve</code> и посмотри что результат тот, который ты ожидал увидеть. Только после этого ты можешь сделать <code>git push</code> своих изменений в наш репозиторий и после этого создать [pull request](https://help.github.com/articles/fork-a-repo/#propose-changes-to-someone-elses-project) - и жди слова благодарности от мейнтейнеров проекта.

### Why so complicated?

Ничего сложного тут нет, просто стоит попробовать и привыкнуть - trust me, I'm engineer.

### Hall of fame

[![Контрибьютор 0](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/0)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/0)
[![Контрибьютор 1](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/1)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/1)
[![Контрибьютор 2](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/2)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/2)
[![Контрибьютор 3](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/3)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/3)
[![Контрибьютор 4](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/4)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/4)
[![Контрибьютор 5](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/5)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/5)
[![Контрибьютор 6](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/6)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/6)
[![Контрибьютор 7](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/images/7)](https://sourcerer.io/fame/sergey48k/SamaraITCommunity/site/links/7)
