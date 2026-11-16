# Планёр — управление съёмками

## Отдельный репозиторий приложения

Этот GitHub-репозиторий содержит только приложение «Планёр», без исходников «Свояков».

Исходники приложения находятся в папке [production-planner](./production-planner).

После включения GitHub Pages сайт публикуется по адресу:

https://czbjcp2yqw-dot.github.io/Mikhael/

Публикация автоматически запускается GitHub Actions из ветки `main`. Для первого включения необходимо:

1. Открыть [Settings → Pages](https://github.com/czbjcp2yqw-dot/Mikhael/settings/pages).
2. В разделе Build and deployment выбрать Source: `GitHub Actions`.
3. Проверить успешность задачи в разделе [Actions](https://github.com/czbjcp2yqw-dot/Mikhael/actions).

Важно: сайт не считается доступным, пока GitHub Pages не подтвердил публикацию.

### Облачная база

Код клиента и серверной функции в репозитории. При этом сама функция и защищённые таблицы размещены в существующем Supabase проекте. Таблицы «Планёра» логически отделены от «Свояков».

Документация по регистрации, ролям и ограничениям: [production-planner/README.md](./production-planner/README.md).
