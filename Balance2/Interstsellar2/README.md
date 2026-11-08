# Интерсцеллар2

Циферблат для Amazfit Balance 2 (Zepp OS), создан в редакторе AmazFace.

![Часы с циферблатом и QR-кодом для установки](Interstsellar2-watch-qr.png)

## Превью циферблата

| Дневной · основной | Ночной | AOD |
| :--: | :--: | :--: |
| ![Дневной · основной](Interstsellar2-watch.png) | ![Ночной](Interstsellar2-night.png) | ![AOD](Interstsellar2-aod.png) |

## Зоны нажатия

Номера на циферблате соответствуют списку справа: там указано, что открывается по нажатию.

![Зоны нажатия](Interstsellar2-tap-zones.png)

- **Версия:** 1.0.0
- **Опубликовано:** 2026-11-08T17:19:49.460Z
- **Установочный пакет:** [Interstsellar2.zpk](https://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Interstsellar2/Interstsellar2.zpk)
- **Ссылка для QR (zpkd1://):** `zpkd1://raw.githubusercontent.com/s7018025085/watchfaces/main/Balance2/Interstsellar2/Interstsellar2.zpk`

## Установка

1. Включите режим разработчика в Zepp App: Профиль → Настройки → О программе → семь раз нажмите на значок Zepp.
2. Профиль → ваши часы → «Режим разработчика» → «Сканировать» (часы должны быть подключены).
3. Отсканируйте QR-код циферблата. Ссылка на пакет постоянная: при обновлении циферблата тот же QR ставит актуальную версию (GitHub CDN может отдавать прежнюю версию до 5 минут).

## Файлы

- `Interstsellar2.zpk` — установочный пакет
- `device.zip` — содержимое для устройства (то же, что внутри пакета)
- `project.zip` — полный проект Zepp OS
- `Interstsellar2-watch.png` — дневной, основной циферблат в полном качестве
- `Interstsellar2-night.png` — ночной циферблат в полном качестве
- `Interstsellar2-aod.png` — превью AOD в полном качестве
- `Interstsellar2-watch-200.png` — уменьшенный дневной мокап высотой 200 px
- `Interstsellar2-watch-qr.png` — мокап часов с циферблатом и QR-кодом
- `Interstsellar2-tap-zones.png` — карта зон нажатия: что открывается по тапу
- `Interstsellar2.watchface.json` — исходник циферблата для редактора AmazFace («Открыть»)
- `amazface-publish.json` — служебный файл AmazFace: защищает папку от случайной перезаписи другим проектом
