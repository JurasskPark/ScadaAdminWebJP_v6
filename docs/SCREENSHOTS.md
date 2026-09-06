# Maintaining the bilingual guide / Обновление двуязычной справки

## Content contract

- Keep the same chapter filenames and image filenames in `ru` and `en`.
- Link each chapter to the same chapter in the other language.
- Describe application workflows. Do not add individual driver, plugin or
  specialized extension operating instructions to this guide.
- Use actual localized button names. Check the running UI and its dictionaries;
  do not translate a Russian button name from memory.

## Capturing screenshots

1. Use a sample project and a consistent theme. The current set uses `default`.
2. Save editor documents before switching the interface language.
3. Select `ru-RU` or `en-GB` through Editor settings and save the language.
4. Wait for confirmation, refresh the main page and reopen the required editors.
   Refresh separate browser pages as well. The settings frame may switch before
   the shell and existing tabs.
5. Check the page heading, tree, active tab title, buttons, table columns and
   dialog text. A selected language option alone is insufficient evidence.
6. Capture the actual UI. Never translate or replace text inside screenshot pixels.
7. Crop to complete controls or a complete dialog. Do not include unrelated
   desktop areas, status-bar license owner information or clipped text fragments.
8. Add documentation captions outside the screenshot, in the guide's language.
   Keep the UI crop at its original pixel scale; do not enlarge a blurred image.
9. Match the purpose and visible state of the Russian and English images.
10. Check every local link, heading anchor and image, and return the application
    to the user's original language after capture.

Project names, device names, filenames, paths and technical identifiers are
project data and need not change language. A collapsed language selector may
list languages by their native names. Neither case is a stale interface translation.

## Current image set

Captured and visually reviewed on 2026-09-06 at a browser viewport of 1355 × 809.
There are 10 PNGs per language: nine actual page states plus a toolbar crop from
the main-window screenshot. The main-window crop omits the status bar; the
new-project image shows the name entry area; tab settings show their upper part.

The screenshots show the editor, not a login/logout test. Creating a project,
saving project data, importing, uploading, downloading and restarting services
were not executed for these illustrations. Their instructions were checked
against the application source and current project documentation. Only editor
language settings were changed, then restored to Russian.

Opening the upload parameter page is separate from running a transfer. Do not
execute deployment merely to obtain a documentation image.

`screenshots.json` records the source dimensions and crop bounds for each image.
Old files in the root `assets` directory are retained for existing external
links; the current guide uses only `ru/assets` and `en/assets`.

## Краткие правила на русском

- Для русской справки снимайте русскую локализацию, для английской — английскую.
- После сохранения языка обновляйте оболочку и повторно открывайте редакторы.
  Проверяйте реальные надписи, а не только выбранный язык в настройках.
- Не переводите текст поверх готового снимка. Обрезайте лишнее окружение,
  сохраняя целыми показанные поля и кнопки; подписи добавляйте снаружи.
- Сохраняйте одинаковый состав разделов и иллюстраций обеих версий.
- Имена файлов и данные проекта не обязаны переводиться вместе с интерфейсом.
- Не запускайте передачу конфигурации и не меняйте рабочий проект ради снимков.
- Старые изображения в корневой папке `assets` сохранены для совместимости
  ссылок; в новой справке используются отдельные папки `ru/assets` и `en/assets`.
