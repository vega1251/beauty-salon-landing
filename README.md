# beauty-salon-landing

Комплект для разработки статического портфолио вымышленного салона. Статус — документация подготовлена, реализация впереди.

| Файл | Назначение |
| --- | --- |
| [AGENTS.md](AGENTS.md) | Правила работы Codex |
| [PROJECT_SPEC.md](PROJECT_SPEC.md) | Функциональность и приёмка |
| [DESIGN_SYSTEM.md](DESIGN_SYSTEM.md) | Визуальные правила |
| [LEGAL_REQUIREMENTS.md](LEGAL_REQUIREMENTS.md) | Правовые условия для демо и сайта клиента |
| [CURRENT_STATE.md](CURRENT_STATE.md) | Состояние и допущения |
| [CHANGELOG.md](CHANGELOG.md) | История |
| [.gitignore](.gitignore) | Локальные файлы, исключаемые из Git |
| [CODEX_START_PROMPT.md](CODEX_START_PROMPT.md) | Готовое задание на первую реализацию |

После реализации запусти из корня `py -m http.server 8000 --bind 127.0.0.1`, если установлен Python, и открой `http://127.0.0.1:8000/`. Для проверки подпапки запусти сервер из родительского каталога и открой `/beauty-salon-landing/`.

Для будущей публикации потребуется разрешение владельца. После проверки прав и условий хостинга в GitHub Pages можно выбрать **Settings → Pages → Deploy from a branch** и указать корень согласованной ветки. Проверь HTTPS, работу по адресу вида `https://<owner>.github.io/beauty-salon-landing/` и состав публично доступных файлов. При публикации из корня документация тоже может стать публичной. Если нужно разместить только сайт, выдели согласованный источник публикации с файлами сайта. [Настройка источника GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)