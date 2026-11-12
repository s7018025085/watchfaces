# VostokЕгерь

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](VostokEger-watch-qr.png)

## Превью циферблата

| Дневной · основной | AOD |
| :--: | :--: |
| ![Дневной · основной](VostokEger-watch.png) | ![AOD](VostokEger-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](VostokEger-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-12T17:55:09.730Z
- **Установочный пакет:** [VostokEger.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/VostokEger/VostokEger.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/VostokEger/VostokEger.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `VostokEger.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `VostokEger-watch.png` — дневной, основной циферблат в полном качестве
- `VostokEger-aod.png` — превью AOD в полном качестве
- `VostokEger-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `VostokEger-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `VostokEger-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `VostokEger.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
