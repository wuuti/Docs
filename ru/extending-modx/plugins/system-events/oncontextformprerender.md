---
title: "OnContextFormPrerender"
translation: "extending-modx/plugins/system-events/oncontextformprerender"
---

## Событие: OnContextFormPrerender

Запускается до загрузки формы редактирования контекста. Полезно для запуска пользовательского JavaScript.

Служба: 2 - Manager Access Events
Группа: modContext

## Параметры события

| Имя     | Описание                                         |
| ------- | ------------------------------------------------ |
| key     | Ключ контекста.                                  |
| context | Ссылка на объект modContext.                     |
| mode    | Либо 'upd' или 'new', в зависимости от ситуации. |

## Смотри также

- [Системные события](extending-modx/plugins/system-events "Системные события")
- [Плагины](extending-modx/plugins "Плагины")
