# agent-skills
A collection of reusable AI agent skills

## Джарвис для Obsidian

Скопируйте папку `.agents/skills/jarvis` в `.agents/skills/` проекта, из которого агент будет работать с хранилищем `work work work`. Откройте проект в агенте и начните сообщение с «Джарвис».

> Джарвис, с Анной договорились завтра отправить черновик сметы.

При первом вызове агент изучит существующие заметки и сохранит памятку с правилами хранилища. Если расположение vault не указано в проекте, добавьте путь к нему в сообщение.

[Открыть инструкции навыка](.agents/skills/jarvis/SKILL.md)

## Плагины Obsidian для локальной установки

В [obsidian-plugins](obsidian-plugins/) лежат файлы официальных релизов и лицензии.

| Плагин | Для чего | Минимальная версия Obsidian |
| --- | --- | --- |
| [Tasks 8.6.0](https://github.com/obsidian-tasks-group/obsidian-tasks/releases/tag/8.6.0) | Списки задач из разных заметок, сроки и повторы | 1.13.1 |
| [Dataview 0.5.68](https://github.com/blacksmithgu/obsidian-dataview/releases/tag/0.5.68) | Таблицы и списки на основе свойств заметок | 0.13.11 |
| [QuickAdd 2.33.3](https://github.com/chhoumann/quickadd/releases/tag/2.33.3) | Быстрое создание заметок и добавление записей по шаблону | 1.13.0 |

1. Скопируйте нужные папки из `obsidian-plugins/` в `<папка хранилища>/.obsidian/plugins/`. Например, файл Tasks должен лежать по пути `.obsidian/plugins/obsidian-tasks-plugin/manifest.json`. Если у vault задана другая папка конфигурации, используйте её вместо `.obsidian`.
2. Перезапустите Obsidian. В **Настройки → Сторонние плагины** отключите ограниченный режим, если он включён, и включите нужные плагины.

Заметки Джарвиса читаются в Obsidian и как обычный Markdown. Плагины можно подключать по отдельности.
