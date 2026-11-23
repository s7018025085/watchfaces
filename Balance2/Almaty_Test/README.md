# Almaty Тест

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](Almaty_Test-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](Almaty_Test-watch.png) | ![Ночной](Almaty_Test-night.png) | ![AOD](Almaty_Test-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](Almaty_Test-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-23T18:24:14.095Z
- **Установочный пакет:** [Almaty_Test.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Almaty_Test/Almaty_Test.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Almaty_Test/Almaty_Test.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `Almaty_Test.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `Almaty_Test-watch.png` — дневной, основной циферблат в полном качестве
- `Almaty_Test-night.png` — ночной циферблат в полном качестве
- `Almaty_Test-aod.png` — превью AOD в полном качестве
- `Almaty_Test-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `Almaty_Test-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `Almaty_Test-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `Almaty_Test.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
