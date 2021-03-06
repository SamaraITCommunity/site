+++
title = "Мероприятия"
date = 2018-07-27
description = "Мероприятия Samara IT Community"

# Whether to sort by "date", "order", "weight" or "none". More on that below
sort_by = "weight"

# Used by the parent section to order its subsections.
# Lower values have priority.
weight = 0

# Template to use to render this section page
template = "section.html"

page_template = "page.html"

# How many pages to be displayed per paginated page.
# No pagination will happen if this isn't set or if the value is 0
paginate_by = 0

# Whether to insert a link for each header like the ones you can see in this site if you hover one
# The default template can be overridden by creating a `anchor-link.html` in the `templates` directory
# Options are "left", "right" and "none"
insert_anchor_links = "none"

# Whether the section pages should be in the search index. This is only used if
# `build_search_index` is set to true in the config
in_search_index = true

# Whether to render that section homepage or not.
# Useful when the section is only there to organize things but is not meant
# to be used directly
render = true

# Your own data
[extra]
+++

{{ googlecalendar() }}

В календаре нашего сообщества показаны все мерорпиятия Самары и области. 
Если вы хотите стать докладчиком на одном из наших мероприятий - в настоящий момент приём заявок остановлен.
Подробнее про события организуемые нашим сообществом вы можете ознакомиться ниже.

## [Материалы для докладчиков](bootcamp)

## Hot topics

Ниже перечислены темы, которые **очень** интересуют участников нашего сообщества. Мероприятия станут ярче от докладов про:

- Тестирование UI [Medium]
- LLVM [Novice]
- Контейнеризация [Novice|Medium]
- MongoDB [Advanced]
- Подготовка резюме [Medium]
- UNIX/Linux [Medium]
- Concurrent programming: programming models (actor model, CSP, π-calculus, etc) and implementations 
(async/await, go/coroutines, green threads, continuations, etc) [Advanced]
- Мобильная разработка на Kotlin [Novice]
- spinnaker.io [Novice]
- Системы контроля версий (обзорная, например про [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki)) [Novice]
- Альтернативы Spring (например [Micronaut](https://micronaut.io)) [Novice|Medium]
