# Рентген бизнеса

Альтернативный взгляд ИИ на ваш бизнес — не консультация. Скилл проводит короткое интервью,
находит узкое место и собирает бриф первого проекта автоматизации, который можно написать с ИИ.

## Как установить

Скопируйте ссылку на эту страницу и отправьте своему ИИ-агенту (Claude Code, Codex, Cursor):

> Установи скилл https://github.com/vb-sferai/business-xray

Агент поставит его сам. Потом напишите: «сделай рентген моего бизнеса».

## Что получите

- `business-xray.md` — фактура: как устроен бизнес, узкое место, стресс-тест, куда уходит время, ставки;
- `business-xray.html` — отчёт: один файл, печатается в PDF.

## Для ИИ-агента: как установить

1. Склонируй репозиторий в папку личных скиллов, имя папки — `business-xray`:
   - Claude Code: `git clone https://github.com/vb-sferai/business-xray ~/.claude/skills/business-xray`
   - Codex, Cursor и другие агенты со стандартом Agent Skills: `git clone https://github.com/vb-sferai/business-xray ~/.agents/skills/business-xray`
   - Нет git — скачай https://github.com/vb-sferai/business-xray/archive/refs/heads/main.zip, распакуй в папку скиллов из пункта выше и переименуй `business-xray-main` в `business-xray`.
2. Проверь, что `SKILL.md` лежит прямо в этой папке.
3. Скажи человеку: «Скилл установлен. Напишите: сделай рентген моего бизнеса». Если скилл не виден: в Claude Code попроси человека ввести `/reload-skills`, в Codex — перезапустить агента.

## Claude.ai (веб и десктоп)

Скачайте [business-xray.zip](https://github.com/vb-sferai/business-xray/releases/latest/download/business-xray.zip) и загрузите: Customize → Skills → «+» → Create skill → Upload a skill.
Включите Settings → Capabilities → «Code execution and file creation».

## Любой чат

Скачайте zip со страницы репозитория (Code → Download ZIP). Приложите к первому сообщению или вставьте подряд три файла: `SKILL.md`, `render.md`, `template.html` — и напишите: «сделай рентген моего бизнеса». Отчёт придёт в чат: фактура текстом и HTML блоком кода — сохраните его в файл `.html` и откройте в браузере.

## Что подготовить

5–10 минут рассказа о бизнесе или своей зоне ответственности: чем заняты, кто клиент,
за что платят, что повторяется каждый месяц. Цифры — своими словами, точность не нужна.

## Приватность

Не вставляйте персональные данные клиентов и сотрудников: имена, контакты, суммы сделок.

---

sfer.ai · https://t.me/kgrbnv_bot
