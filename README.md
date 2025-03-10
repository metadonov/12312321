# 🌐 IP Logger с отправкой в Telegram

Простой и стильный сайт для сбора информации о посетителях с автоматической отправкой данных в Telegram бота.

## 📱 Демонстрация работы

Сайт собирает следующую информацию:
- IP-адрес
- Город
- Страна
- Регион
- Интернет-провайдер

## 🛠️ Установка и настройка

### 1. Скачайте файлы
- Скачайте все файлы из репозитория
- Убедитесь что у вас есть:
  - `index.html`
  - `trollface.png`

### 2. Настройка Telegram бота
1. Создайте нового бота у [@BotFather](https://t.me/BotFather)
2. Получите токен бота
3. Получите ваш Chat ID:
   - Напишите [@userinfobot](https://t.me/userinfobot)
   - Бот пришлет вам ваш Chat ID

### 3. Настройка кода
1. Откройте `index.html` в текстовом редакторе
2. Найдите следующие строки:
   ```html
   const botToken = ''; // Токен вашего бота
   const chatId = ''; // Укажите ваш Chat ID
   ```
3. Вставьте ваши данные между кавычками

### 4. Загрузка на хостинг

#### Вариант 1: GitHub Pages
1. Создайте новый репозиторий на GitHub
2. Загрузите все файлы в репозиторий
3. Перейдите в Settings → Pages
4. В разделе "Source" выберите ветку main
5. Нажмите Save
6. Подождите несколько минут до публикации

#### Вариант 2: Netlify
1. Зарегистрируйтесь на [Netlify](https://www.netlify.com/)
2. Нажмите "New site from Git"
3. Выберите ваш репозиторий
4. Следуйте инструкциям по развертыванию

#### Вариант 3: Любой другой хостинг
1. Загрузите файлы на хостинг через FTP или панель управления
2. Убедитесь, что `index.html` находится в корневой директории
3. Убедитесь, что `trollface.png` находится в той же директории, что и `index.html`

## ⚠️ Важные примечания

1. **Безопасность**
   - Не публикуйте токен бота и Chat ID в публичных репозиториях
   - Рекомендуется использовать переменные окружения для хранения чувствительных данных

2. **Ограничения**
   - API ipapi.co имеет ограничения на количество запросов
   - Некоторые антивирусы могут блокировать сбор IP информации

3. **Правовые аспекты**
   - Убедитесь, что вы соблюдаете законы о персональных данных в вашей стране
   - Рекомендуется добавить уведомление для пользователей о сборе данных

## 📝 Лицензия

Этот проект распространяется под лицензией MIT. Подробности в файле [LICENSE](LICENSE).