# Self-Correcting Public Link Parser

[Русский](../README.md) · [English](README.en.md) · **Українська** · [中文](README.zh-CN.md) · [עברית](README.he.md)

> Незалежний продукт; він не пов’язаний із Google LLC, Max, WhatsApp, Telegram або ZennoPoster і не схвалений ними.

## Огляд

Комерційний процес для збирання, нормалізації, перевірки та експорту публічно доступних посилань із результатів пошуку для досліджень, каталогізації й аналітики.

## Як відбувається збір

1. Визначаються законна мета, дозволені домени, виключення, регіони, мови, формат і ліміти швидкості.
2. Створюється черга погоджених пошукових запитів зі статусами та датами запуску.
3. Обробляються лише сторінки без авторизації з дотриманням правил джерела, `robots.txt` там, де застосовно, пауз і лімітів.
4. Витягуються лише необхідні публічні поля: URL, заголовок, видимий фрагмент, запит і дата.
5. URL канонізуються, приватні, службові та нерелевантні сторінки відхиляються.
6. Дублікати усуваються за канонічним URL і доменом; походження зберігається.
7. Самокорекція означає контроль якості та перехід між заздалегідь погодженими профілями або ручну перевірку, а не обхід захисту.
8. Формується очищений CSV, JSON або таблиця з походженням і журналом фільтрації.

## Ціна і контакти

- Поточна ціна оффера: **$50**.
- Telegram: [@TheBotsLab](https://t.me/TheBotsLab)
- E-mail: [BotsLab@proton.me](mailto:BotsLab@proton.me)

## Responsible-use boundary

Use only for publicly available URLs and for an agreed lawful purpose. The product does not bypass authentication, CAPTCHA, technical protections, platform limits, or access controls. It must not be used for spam, mass messaging, unauthorised profiling, or collection of unnecessary personal data.
