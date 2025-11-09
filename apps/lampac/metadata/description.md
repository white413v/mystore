# Lampac

Lampac — сервер плагинов для Lampa, предоставляющий доступ к онлайн-стримингу, торрентам, 18+ контенту и DLNA.

## Функции
- Плагины: online.js (стриминг), dlna.js (DLNA), sync.js (синхронизация).
- Админ-панель: /admin для редактирования init.conf (порты, прокси, токены).
- Поддержка: TorrServer, Jackett, ImageMagick (для изображений).
- Архитектуры: amd64, arm64, armv7.

## Установка
После установки доступ: по поддомену (lampac.yourdomain.com) или IP:9118. В Lampa добавьте URL плагинов: http://your-subdomain:9118/online.js.

## Кастомизация
- Редактируйте init.conf в ${APP_DATA_DIR}/config (на сервере) или через форму установки.
- Для PRO: Добавьте токены (Filmix, etc.) в init.conf.
- DLNA: Разместите медиа в ${APP_DATA_DIR}/dlna.
- Отключите функции: В init.conf укажите "PornHub": {"enable": false}.

## Зависимости
Нет внешних; опционально — Tor (для .onion) на порту 9050.
