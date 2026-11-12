# Amazfit black

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](Amazfit_black-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](Amazfit_black-watch.png) | ![Ночной](Amazfit_black-night.png) | ![AOD](Amazfit_black-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](Amazfit_black-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-12T16:55:47.436Z
- **Установочный пакет:** [Amazfit_black.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Amazfit_black/Amazfit_black.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Amazfit_black/Amazfit_black.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `Amazfit_black.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `Amazfit_black-watch.png` — дневной, основной циферблат в полном качестве
- `Amazfit_black-night.png` — ночной циферблат в полном качестве
- `Amazfit_black-aod.png` — превью AOD в полном качестве
- `Amazfit_black-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `Amazfit_black-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `Amazfit_black-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `Amazfit_black.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
