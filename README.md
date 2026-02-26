# Data-Driven Decision Making

**Университет:** Университет ИТМО
**Курс:** Data-Driven Decision Making
**Семестр:** 4-й семестр

---

## Команда

| Имя | GitHub |
|-----|--------|
|     |        |
|     |        |
|     |        |
|     |        |

---

## Содержание репозитория

Здесь хранятся лабораторные работы по дисциплине Data-Driven Decision Making.

---

## Инструкция для команды

### 1. Установка Git

Скачайте и установите Git: https://git-scm.com/downloads

Настройте имя и почту (один раз):
```bash
git config --global user.name "Ваше Имя"
git config --global user.email "your@email.com"
```

---

### 2. Клонирование репозитория

Выберите папку, где хотите хранить проект, откройте там терминал и выполните:

```bash
git clone https://github.com/andreyvalenchuk/Data-Driven-Decision-Making.git
```

После этого появится папка `Data-Driven-Decision-Making` — это и есть ваш локальный репозиторий.

---

### 3. Подключение к существующей локальной папке

Если у вас уже есть папка с файлами и вы хотите связать её с этим репозиторием:

```bash
# Перейдите в свою папку
cd путь/к/вашей/папке

# Инициализируйте git (если ещё не сделано)
git init

# Подключите удалённый репозиторий
git remote add origin https://github.com/andreyvalenchuk/Data-Driven-Decision-Making.git

# Получите актуальное состояние с GitHub
git pull origin main --allow-unrelated-histories
```

---

### 4. Ежедневная работа: получить обновления

Перед началом работы всегда тяните последние изменения от команды:

```bash
git pull origin main
```

---

### 5. Публикация (push) своих результатов

После того как выполнили работу и хотите залить её на GitHub:

```bash
# Посмотреть, какие файлы изменились
git status

# Добавить нужные файлы в коммит (или . для всех)
git add имя_файла
# или все сразу:
git add .

# Создать коммит с описанием
git commit -m "Описание: что сделали (например, lab1 - EDA завершена)"

# Отправить на GitHub
git push origin main
```

---

### 6. Рекомендации по структуре папок

Рекомендуется хранить работы в отдельных папках по лабораторным:

```
Data-Driven-Decision-Making/
├── lab1/
│   ├── notebook.ipynb
│   └── data/
├── lab2/
│   └── ...
└── README.md
```

---

### 7. Если возник конфликт при push

Если GitHub отклонил push (`rejected`), значит у кого-то из команды есть изменения, которых нет у вас:

```bash
# Сначала подтяните изменения
git pull origin main

# Разрешите конфликты (если есть), затем снова:
git push origin main
```

---

> При возникновении вопросов — пишите в чат команды.
"# Data-Driven-Decision-Making" 
