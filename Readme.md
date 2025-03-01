# Дипломный проект: Cайт-агрегатор просмотра и бронирования гостиниц

## Описание

Этот проект представляет собой сервис бронирования отелей, разработанный в рамках курса Fullstack-разработчик на JavaScript.

---

## Запуск приложения

Следуйте шагам ниже для успешного запуска проекта.

### Шаг 1. Клонирование репозитория

Клонируйте проект с помощью команды:

```bash
git clone --recurse-submodules <url-репозитория>
```

---

### Шаг 2. Настройка переменных окружения

1. В корневой директории проекта скопируйте файл `.env-example` и переименуйте его в `.env`:

   ```bash
   cp .env-example .env
   ```

2. Откройте файл `.env` и заполните необходимые переменные окружения:

| Переменная                   | Описание                                  | Пример                 |
| ---------------------------- | ----------------------------------------- | ---------------------- |
| `MONGO_INITDB_ROOT_USERNAME` | Имя пользователя для доступа к MongoDB    | `root`                 |
| `MONGO_INITDB_ROOT_PASSWORD` | Пароль пользователя для доступа к MongoDB | `qwerty`               |
| `HTTP_HOST`                  | IP-адрес хоста или `localhost`            | `http://192.168.0.100` |
| `SECRET`                     | Секретный ключ для JWT авторизации        | `123456789`            |

---

### Шаг 3. Сборка и запуск контейнеров

Для сборки и запуска приложения выполните команду (для Linux с правами суперпользователя):

```bash
sudo docker compose up --build
```

---

### Шаг 4. Открытие приложения в браузере

После успешного запуска перейдите в браузер и откройте страницу по адресу, указанному в переменной `HTTP_HOST`.

---

### Шаг 5. Вход в систему

Для начала работы в системе уже создан пользователь с правами администратора. Используйте следующие данные для входа:

- **Email**: `admin@admin`
- **Пароль**: `admin1`

---

### Шаг 6. Готово!

Сервис бронирования отелей запущен и готов к использованию.

---

## Требования

Для работы приложения необходимы:

- Установленный Docker и Docker Compose.
- Доступ к IP-адресу, указанному в переменной `HTTP_HOST`.

## mongo-express
- Для удобства установлен Веб-интерфейс администратора MongoDB (admin:pass) 




