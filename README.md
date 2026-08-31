# ATLAS — правові документи

Статичні сторінки для подання застосунку в App Store і Google Play.
Без збірки й залежностей.

| Сторінка | Українською | English |
|---|---|---|
| Політика приватності | [uk/privacy.html](uk/privacy.html) | [en/privacy.html](en/privacy.html) |
| Умови використання | [uk/terms.html](uk/terms.html) | [en/terms.html](en/terms.html) |
| Видалення акаунта | [uk/delete-account.html](uk/delete-account.html) | [en/delete-account.html](en/delete-account.html) |
| Підтримка | [uk/support.html](uk/support.html) | [en/support.html](en/support.html) |

## Контакти

Володілець даних — JenkinsLab, м. Ужгород, Україна.
Звʼязок: <betench2@gmail.com>

## Куди подаються посилання

| Поле в сторі | Сторінка |
|---|---|
| Privacy Policy URL (Apple, Google Play) | `en/privacy.html` |
| Support URL (Apple) | `en/support.html` |
| Account deletion URL (Google Play) | `en/delete-account.html` |
| Terms of Use / EULA | `en/terms.html` |

Рев'юери працюють англійською, тому в поля стору подавайте англійські версії.
Українські лишаються для користувачів; сторінки звʼязані перемикачем мови в
обидва боки.

## Розгортання через GitHub Pages

Settings → Pages → Source: **Deploy from a branch**, гілка `main`, тека `/`.
Адреси матимуть вигляд:

```
https://ryslansn.github.io/TravelP/en/privacy.html
```

Репозиторій має бути публічним — Pages з приватного потребує платного плану.

URL мусить лишатися стабільним: він потрапляє в лістинг стору, і зміна адреси
означає оновлення подання.

## Про зміст

Сторінки описують фактичну поведінку застосунку, а не наміри.

Зокрема твердження «застосунок не запитує місцезнаходження» правдиве буквально:
у зібраному застосунку не оголошено жодного дозволу на доступ до локації.
Координати місця беруться з того, куди користувач натиснув на мапі. **Якщо
колись зʼявиться кнопка «Моє місце» — цю обіцянку треба переписати разом із
маніфестом.**
