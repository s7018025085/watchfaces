# Звёздный рубеж

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](Zvezdnyy_rubezh-watch-qr.png)

## Превью циферблата

| Дневной · основной | AOD |
| :--: | :--: |
| ![Дневной · основной](Zvezdnyy_rubezh-watch.png) | ![AOD](Zvezdnyy_rubezh-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](Zvezdnyy_rubezh-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-12T17:51:47.557Z
- **Установочный пакет:** [Zvezdnyy_rubezh.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Zvezdnyy_rubezh/Zvezdnyy_rubezh.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Zvezdnyy_rubezh/Zvezdnyy_rubezh.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `Zvezdnyy_rubezh.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `Zvezdnyy_rubezh-watch.png` — дневной, основной циферблат в полном качестве
- `Zvezdnyy_rubezh-aod.png` — превью AOD в полном качестве
- `Zvezdnyy_rubezh-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `Zvezdnyy_rubezh-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `Zvezdnyy_rubezh-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `Zvezdnyy_rubezh.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
