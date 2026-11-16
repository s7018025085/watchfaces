# Contra test

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](Contra_test-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](Contra_test-watch.png) | ![Ночной](Contra_test-night.png) | ![AOD](Contra_test-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](Contra_test-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-16T03:29:48.666Z
- **Установочный пакет:** [Contra_test.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Contra_test/Contra_test.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Contra_test/Contra_test.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `Contra_test.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `Contra_test-watch.png` — дневной, основной циферблат в полном качестве
- `Contra_test-night.png` — ночной циферблат в полном качестве
- `Contra_test-aod.png` — превью AOD в полном качестве
- `Contra_test-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `Contra_test-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `Contra_test-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `Contra_test.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
