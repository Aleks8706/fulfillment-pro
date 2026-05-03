# 📦 Фулфилмент Про — Система управления складом

[![CI](https://github.com/your-username/fulfillment-pro/actions/workflows/ci.yml/badge.svg)](https://github.com/your-username/fulfillment-pro/actions/workflows/ci.yml)
[![Pages](https://github.com/your-username/fulfillment-pro/actions/workflows/deploy-pages.yml/badge.svg)](https://your-username.github.io/fulfillment-pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> 🚀 Полнофункциональная система учёта склада: приёмка, отгрузка, инвентаризация, задачи, сотрудники.

## ✨ Возможности

- 📊 Дашборд с аналитикой и графиками
- 🏭 Учёт товаров с фото, категориями, местами хранения
- 📥 Приёмка с поддержкой сканера штрихкодов и камеры
- 📤 Отгрузка с контролем остатков
- ✅ Задачи с приоритетами и назначением сотрудникам
- 👥 Учёт сотрудников с онлайн-статусом и часами работы
- 📋 Инвентаризация с актами и расхождениями
- 🏷️ Печать этикеток (58×40, 58×30, 100×80 мм)
- 📄 Генерация и печать документов (акты, накладные)
- 🔐 Ролевая авторизация (admin/manager/picker)
- 🔔 Система уведомлений
- 🤖 Чат-бот «ФулфиБот» с контекстными ответами

## 🚀 Быстрый старт

### 🌐 Демо на GitHub Pages

👉 [Открыть демо-версию](https://your-username.github.io/fulfillment-pro)

**Демо-доступы:**
| Логин | Пароль | Роль |
|-------|--------|------|
| `admin@fulfillment.pro` | `admin123` | Полный доступ |
| `manager@fulfillment.pro` | `manager123` | Менеджер |
| `picker@fulfillment.pro` | `picker123` | Сборщик |

> ⚠️ Демо работает на `localStorage` — данные хранятся только в вашем браузере.

### 🐳 Локальный запуск с бэкендом

```bash
# Клонировать репозиторий
git clone https://github.com/your-username/fulfillment-pro.git
cd fulfillment-pro

# Скопировать пример .env
cp backend/.env.example backend/.env
# Отредактировать backend/.env при необходимости

# Запустить через Docker
docker-compose up -d

# Открыть в браузере:
# Фронтенд: http://localhost:8080
# API: http://localhost:3000/api/health
