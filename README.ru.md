# ComfyUI Google Colab Template

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maybeoff/google-colab/blob/main/ipynb/clear_ComfyUI.ipynb)

Готовый шаблон для запуска **ComfyUI** в Google Colab. Полностью автоматизированная настройка — генерируй изображения в облаке без лишних усилий.

## Возможности

- Автоматически устанавливает последнюю версию ComfyUI прямо из репозитория
- Три варианта туннелирования на выбор:
  - **Cloudflare** — быстро и надёжно (не работает в России)
  - **tuna.am** — стабильный сервис для пользователей из России и СНГ (требует регистрации и токена)
  - **LocalTunnel** — простой и быстрый вариант
- Все зависимости устанавливаются автоматически

## Как использовать

1. Открой ноутбук в Colab по кнопке выше
2. Включи GPU: `Runtime` → `Change runtime type` → `T4 GPU`
3. Запусти ячейку установки ComfyUI
4. Скачай нужные модели (Checkpoints, VAE, LoRA)
5. Выбери способ туннелирования и запусти соответствующую ячейку
6. Перейди по сгенерированной ссылке — ComfyUI готов к работе

> Для tuna.am нужно зарегистрироваться на [tuna.am](https://tuna.am) и вставить токен в соответствующее поле.

---

*Автор: [Maybeoff](https://github.com/maybeoff)*
