# Инструкция по запуску расширенной Лиры v2

## 🔐 Обязательные подключения

1. Supabase: https://supabase.com
2. OpenAI API: https://platform.openai.com/account/api-keys
3. Telegram Bot API: https://t.me/BotFather
4. Netlify CLI: https://docs.netlify.com/cli/get-started/

## 🚀 Новые возможности

- 📥 Автоматическая загрузка памяти из memory.json
- ✅ Редактор задач с возможностью отметки выполнения
- 🤖 Telegram-бот через Webhook
- ☁️ Реальный деплой через Netlify CLI

## 🔗 Telegram Webhook

Создай бота и настрой Webhook через сервер или Ngrok.

## 💻 Netlify CLI

```bash
npm install -g netlify-cli
netlify login
netlify init
netlify deploy --prod
```
