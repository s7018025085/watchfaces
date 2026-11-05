# СС Digital

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](SS_Digital-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](SS_Digital-watch.png) | ![Ночной](SS_Digital-night.png) | ![AOD](SS_Digital-aod.png) |

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-05T18:08:23.245Z
- **Установочный пакет:** [SS_Digital.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/SS_Digital/SS_Digital.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/SS_Digital/SS_Digital.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `SS_Digital.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `SS_Digital-watch.png` — дневной, основной циферблат в полном качестве
- `SS_Digital-night.png` — ночной циферблат в полном качестве
- `SS_Digital-aod.png` — превью AOD в полном качестве
- `SS_Digital-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `SS_Digital-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `SS_Digital.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
