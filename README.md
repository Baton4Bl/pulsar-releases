# Pulsar

Диагностика, мониторинг и обслуживание ПК для Windows.

**Скачать:** [Pulsar.exe](https://github.com/Baton4Bl/pulsar-releases/raw/main/Pulsar.exe) — версия 13.5.
Контрольная сумма SHA-256 — в файле `Pulsar.exe.sha256`.

Сайт: https://pulsar.wisp.uno
Discord-сервер: https://discord.gg/EDJ5csV7hh

Программа обновляется сама. Автор и поддержка — Discord: babony.

## Безопасность

Если антивирус или Windows предупреждают о Pulsar — это ложное срабатывание (нет платной подписи, программа работает с драйверами и настройками Windows).
Как проверить файл самому: https://pulsar.wisp.uno/security/

- **Отпечаток:** Win + X → «Терминал» → `Get-FileHash "$env:USERPROFILE\Downloads\Pulsar.exe"` (или `Get-FileHash`, пробел и перетащить файл в окно) — строка Hash должна совпасть с `Pulsar.exe.sha256`.
