# Todo List — React (FSD) + json-server / localStorage

Todo-list приложение на **React**, реализованное с использованием **FSD (Feature-Sliced Design)**, собственной логикой роутинга, работой с сервером через `json-server` в режиме разработки и `localStorage` в продакшене.  
Проект включает кастомные анимации и задеплоен на GitHub Pages.

## 🔗 Live Demo
👉 https://vadimandrushenko.github.io/todo-react/  

---

## 🚀 Возможности
- CRUD операции с задачами (создание, редактирование, удаление, выполнение)
- Архитектура FSD
- Собственный hash-роутинг (подходит для GitHub Pages)
- Работа с API через `json-server` (dev)
- Хранение данных в `localStorage` (production)
- Кастомные анимации элементов списка

  
---

## ⚙️ Установка и запуск

### 1. Клонирование репозитория
```bash
git clone https://github.com/VadimAndrushenko/todo-react.git  
cd todo-react
```

### 2. Установка зависимостей
```bash
npm install
```

### 3. Запуск в режиме разработки
Откройте два терминала (или запустите параллельно):

Запускаем json-server (mock API):
```bash
npm run sever
```

Запускаем frontend (dev сервер):

```bash
npm run dev
```

переходите по сылке http://localhost:5173/
