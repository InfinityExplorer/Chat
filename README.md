# Real-Time Chat Application

Простой, но мощный чат в реальном времени с использованием современных технологий. Проект включает:

- **Бэкенд**: ASP.NET Core с SignalR для обработки WebSocket-соединений
- **Кэширование/Брокер сообщений**: Redis в Docker-контейнере
- **Фронтенд**: React с Tailwind CSS для стилизации
- **Полная контейнеризация** через Docker Compose

## 🛠 Технологии

**Бэкенд:**
- ASP.NET Core 7.0
- SignalR
- Redis (для масштабирования SignalR Backplane)

**Фронтенд:**
- React 18
- TypeScript
- Tailwind CSS 3
- SignalR Client

**Инфраструктура:**
- Docker 20.10+
- Docker Compose 2.15+

## 🚀 Быстрый старт

### Предварительные требования
- [Docker](https://www.docker.com/) (+ Docker Compose)
- [.NET SDK 7.0](https://dotnet.microsoft.com/) (только для разработки бэкенда)
- [Node.js 18.x](https://nodejs.org/) (только для разработки фронтенда)
