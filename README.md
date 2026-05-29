# speed-skating-timing

Система старта и финиша для соревнований по скоростным роликам — ТЗ, функциональное описание, спецификации модулей.

## Документация

| Файл | Содержание |
|------|------------|
| [TZ.md](TZ.md) | Техническое задание |
| [functional.md](functional.md) | Функциональное описание |
| [start-unit.md](start-unit.md) | Стартовый модуль (ESP32) |
| [camera.md](camera.md) | Камера фото-финиша |
| [cost-mvp-no-rfid.md](cost-mvp-no-rfid.md) | Смета MVP без RFID (Pi 5 уже куплен) |
| [moscow-components.md](moscow-components.md) | Компоненты в Москве, датчики линии, камера 120 fps |
| [rfid-transponders.md](rfid-transponders.md) | UHF-транспондеры (RFID), фаза 2, рынок РФ |
| [rfid-diy/](rfid-diy/README.md) | DIY-проекты RFID-хронометража (подробно по каждому) |

## Репозитории

| Платформа | URL | Remote |
|-----------|-----|--------|
| **GitHub** (основной) | https://github.com/andybeg/speed-skating-timing | `origin` |
| **GitFlic** (зеркало) | https://gitflic.ru/project/andybeg/speed-skating-timing | `gitflic` |

```bash
git clone --recurse-submodules git@github.com:andybeg/speed-skating-timing.git
# или
git clone --recurse-submodules git@gitflic.ru:andybeg/speed-skating-timing.git
```

Субмодули: [rfid-diy](https://gitflic.ru/project/andybeg/rfid-diy) (DIY RFID, GitFlic). Если клонировали без `--recurse-submodules`: `git submodule update --init`.

Синхронизация зеркала на GitFlic: `git push gitflic main`
