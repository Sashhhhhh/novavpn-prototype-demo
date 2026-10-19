# Авторство картинок

## Flowbite Illustrations — MIT

`flowbite-set-done.svg` — «woman-rocket-flying» из Flowbite Illustrations, https://flowbite.com/illustrations/. Перекрашено в бренд NovaVPN: синий `#2563eb` → `#C8571F`, светлые оттенки — в оранжевые. Решение №110, запись 064.

Иллюстрации трёх узлов — выбор владельца по картинке кандидатов, решение №129, запись 076. Скачаны 12.10.2026 тёмным вариантом из `src/3d/dark/` репозитория, каждый файл — в свою пустую папку, проверены на скрипты и внешние ссылки. Перекраска — тем же правилом, что у `flowbite-set-done.svg`: таблица замен синих тонов, остальные синие оттенки — поворотом тона к 20°.

| Файл | Исходник Flowbite | Где на экране | Особенность |
|---|---|---|---|
| `flowbite-login.svg` | woman-cyber-security | AUTH-1 «Вход» | — |
| `flowbite-login-closed.svg` | laptop-server-error | AUTH-1 «Вход закрыт» | — |
| `flowbite-region.svg` | woman-map | REGION «Регион» | карта — встроенный PNG 1068 × 719, заменой цветов не берётся: синий → оранжевый поворотом тона 160°. Прежде — фильтром `<feColorMatrix type="hueRotate">` в самом SVG; WebKit растрирует фильтр в низком разрешении, и на плотности 3 края штатов шли лесенкой — М3 третьей приёмки «Главная и пейвол», запись 094. С записи 098 PNG перекрашен заранее в полном разрешении той же матрицей `hueRotate` 160° — на неумноженных значениях sRGB, как у фильтра, — и вставлен без фильтра; сверено: `hue-rotate(160deg)` холста Chromium по исходному PNG — разница 0 на всех непрозрачных пикселях; рендер Chromium до и после — средняя разница 0.02 из 255 на плотности 3 |
| `flowbite-invite.svg` | balloon-package-flying | INVITE «Пригласить друга» | — |
| `flowbite-banner-year.svg` | store-discount-open | HOME, баннер «Продлить на год» | «если поместится» — по замеру на узкой раме |
| `flowbite-paywall.svg` | people-connecting | PAYWALL «Что даёт Premium» | с 20.10.2026, решение №188: прежний gaming-controller-ghosts, №130, — «не про VPN»; выбран владельцем из четырёх названий, скачан в свою папку, 38 490 байт, проверен на скрипты и ссылки, перекрашен скриптом `tools/scripts/flowbite-перекраска.py` — правило восстановлено записью 110, прогон по готовым картинкам не меняет ни одного цвета; «сделай чуть больше на 10%» — `viewBox` срезан по бокам на 35,6 из 783, рисунок в той же колонке крупнее в 1,1 раза, верх и низ целы — пучок волос у верхнего края |
| `flowbite-gift.svg` | woman-scooter-transporting | GIFT «Ваучер в подарок» | выбран из четырёх кандидатов на экране, решение №179; скачан 13.10.2026 в свою папку, проверен на скрипты и ссылки, перекрашен тем же правилом |

Copyright (c) 2025 Themesberg — `LICENSE` репозитория https://github.com/themesberg/flowbite-illustrations, сверено 11.10.2026.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Снимки Happ и INCY — лист «Как добавить ключ»

Сняты владельцем на своём iPhone 12.10.2026, присланы в Telegram. Сторонние приложения — интерфейс принадлежит их авторам; снимки показывают человеку, куда вставить ключ, решения №78 и №118.

| Файл | Приложение | Язык | Что в кадре | Вырезка |
|---|---|---|---|---|
| `happ-howto-ru.jpg` | Happ, версия на экране не видна | русский | меню «+»: «Вставить из буфера обмена» | верх экрана 4:3, 800 × 600 |
| `happ-howto-en.jpg` | Happ | английский | меню «+»: «Import from clipboard» | верх экрана 4:3, 800 × 600 |
| `incy-howto-ru.jpg` | INCY v2.6.2 | русский | «Добавить», «Вставить» на пустом экране | низ экрана 4:3, 800 × 600 |
| `incy-howto-en.jpg` | INCY v2.6.2 | английский | «Add», «Paste» | низ экрана 4:3, 800 × 600 |

Персональных данных в вырезке нет: HWID телефона в кадре Happ ниже вырезки. Исходники — у владельца, в репозиторий не кладутся. Язык снимка — по языку кабинета: русский — русский, английский и туркменский — английский.
## Флаги стран — circle-flags, MIT

`flags/ru.svg`, `flags/tm.svg`, `flags/gb.svg`, `flags/ae.svg` — круглые флаги из https://github.com/HatScripts/circle-flags, ветка `gh-pages`, папка `flags/`. Выбор региона, круглые флаги стран — решение №122, запись 074; скачано с разрешения владельца 12.10.2026. Не перекрашены. Россия и Туркменистан — страны кабинета; Великобритания и ОАЭ — пример длинных названий в каталоге.

Лицензия — `LICENSE.md` репозитория, сверено через GitHub API 12.10.2026:

Copyright (c) 2026 HatScripts

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.