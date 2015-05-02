# WP-PluginsUsed на русском #

**Автор:** [Lester Chan](http://lesterchan.net/wordpress/readme/wp-pluginsused.html)

**Автор перевода:** Анна Озерицкая

Создает список установленных на вашем сайте плагинов для WordPress - как включённых, так и отключённых.

## Загрузка нужной версии ##

**Для WordPress 2.6.x - 2.7.x:** [WP-PluginsUsed 1.40 (9,5 Кб)](http://l10n-ru.googlecode.com/files/wp-pluginsused-1.40-ru_RU.zip)

**Для WordPress 2.8.x:** [WP-PluginsUsed 1.50 (9,7 Кб)](http://l10n-ru.googlecode.com/files/wp-pluginsused-1.50-ru_RU.zip)

## Установка и использование ##

  1. Скачайте и распакуйте архив.
  1. Загрузите папку `wp-pluginsused` в папку с плагинами на вашем сайте (обычно `wp-content/plugins/`).
  1. Включите плагин.
  1. Для того, чтобы создать список плагинов, создайте новую запись или страницу и вставьте в её текст этот код:
```
[stats_pluginsused]
<h2>Включённые плагины</h2>
[active_pluginsused]
<h2>Отключённые плагины</h2>
[inactive_pluginsused]
```