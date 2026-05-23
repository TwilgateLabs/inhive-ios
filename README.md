# InHive — iOS

[![TestFlight](https://img.shields.io/badge/iOS-TestFlight%20closed%20beta-blue)](https://t.me/InHive_support_bot)
[![Platform](https://img.shields.io/badge/platform-iOS%2015%2B-lightgrey)](https://t.me/InHive_support_bot)

InHive — кроссплатформенный VPN-клиент. Этот репозиторий — публичная точка для iOS-сборок.

## 🍎 Как получить iOS-сборку

**Сборка раздаётся по приглашению через Apple TestFlight.** Публичной IPA здесь не будет, пока не закроется Apple Developer Program enrollment организации (см. ниже).

Чтобы получить инвайт:

1. Напиши в саппорт-бот → **[@InHive_support_bot](https://t.me/InHive_support_bot)**
2. В ответ придёт TestFlight-ссылка
3. Открой её на iPhone/iPad → установи приложение **TestFlight** из App Store если ещё нет → нажми "Accept" → "Install"

**Требования:** iOS 15.0 или новее. Универсальный билд — iPhone, iPad, Apple Silicon Mac (через Designed for iPad).

## 📅 App Store status

Подача в App Store временно отложена до завершения регистрации организации в Apple Developer Program (юр. лицо `twilgate`). Текущий рейтинг submission — pending; следим в [новостях](https://inhive.ru/news).

В этом промежутке iOS-доставка идёт **только через TestFlight closed beta** — это полностью соответствует Apple Beta Testing policy.

## 🔗 Связанные репозитории

- [TwilgateLabs/inhive-core](https://github.com/TwilgateLabs/inhive-core) — Go-ядро (sing-box 1.13 fork; iOS xcframework сборка через `make ios`)
- [twilgate/inhive-web](https://github.com/twilgate/inhive-web) — Web (private; `inhive.ru`)

## 🔒 Безопасность

Если ты нашёл security issue:

- **Не открывай публичный GitHub issue.**
- Пиши в **[@InHive_support_bot](https://t.me/InHive_support_bot)** с темой `SECURITY`.
- Coordinated disclosure — стандартный 90-дневный embargo (см. `docs/adr/009-stealth-security-releases.md` в `inhive-memory`).

## 📜 Лицензия

Этот mirror-repo (только release notes / TestFlight handoff) не содержит исходного кода. Источники iOS — в [twilgate/inhive-app](https://github.com/twilgate/inhive-app) (private). Go-ядро — Apache 2.0 (sing-box upstream + наш patch set), см. [TwilgateLabs/inhive-core](https://github.com/TwilgateLabs/inhive-core/blob/main/LICENSE).
