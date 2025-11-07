# 🌿 HabitFlow — Habit Tracker with Firebase & Nuxt 3

**HabitFlow** — это современное приложение для отслеживания привычек,  
созданное на **Nuxt 3 + TypeScript + Firebase**.  
Оно помогает пользователям формировать позитивные привычки,  
анализировать прогресс и получать советы от AI (в будущем релизе).

---

## ✨ Основные возможности

- ✅ Регистрация и вход через **Firebase Authentication**
- 🧱 Управление привычками (создание, удаление, отображение)
- 📊 Хранение данных в **Cloud Firestore**
- 📈 Аналитика выполнения привычек (в планах)
- 🤖 AI-помощник (в планах, через OpenAI API)
- 🌗 Тёмная тема и адаптивный интерфейс
- ⚡ SSR + SPA режимы (Nuxt 3)
- 💾 Развёртывание через **Vercel / Netlify**

---

## 🧰 Технологический стек

| Технология | Использование |
|-------------|----------------|
| **Nuxt 3** | SSR/SPA фреймворк для Vue 3 |
| **TypeScript** | Статическая типизация |
| **Pinia** | Управление состоянием |
| **Firebase Auth** | Аутентификация пользователей |
| **Cloud Firestore** | Хранение данных |
| **TailwindCSS** | UI-стилизация |
| **OpenAI API** | (в будущем) AI-анализ привычек |
| **Vercel** | Хостинг и CI/CD |


## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
