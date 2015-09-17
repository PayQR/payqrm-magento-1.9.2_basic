Модуль PayQR для Magento CMS 1.x.x

- Версия модуля 1.0.0
- Версия API 1.0.2
- Версия библиотеки обработчика API 1.0.2

Для обновления обработчика нужно:
1) заменить содержимое папки payqr/classes новыми файлами
2) в файле app/code/community/PayQR/Payment/etc/config.xml
   в секции <default> установить актуальное значение <version_api>
3) в Админпанели зайти в секцию System->Configuration->Payment Methods и сохранить конфигурацию для перезаписи файла payqr_config.php