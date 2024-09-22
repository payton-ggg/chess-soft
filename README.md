# Chess Hack JS 🎉

## Описание 📝

**Chess Hack JS** — скрипт для шахмат, который автоматически находит лучший ход с помощью Stockfish. Анализирует состояние доски, генерирует FEN-строку и подсвечивает лучший ход на доске. ♟️

### Функции ⚙️
Проверка наличия шахматной доски перед запуском. Выбор цвета игрока (белые или черные).
 Генерация FEN-строки для анализа.
 Взаимодействие с шахматным движком Stockfish.
 Подсветка лучших ходов на доске.
 Возможность перезагрузки скрипта.

## Как использовать 🚀

1. **Подключите скрипт**:
   ```html
   <script src="https://cdn.jsdelivr.net/gh/quickyyy/chesshackjs@main/%D0%B0bobus2.js"></script>
   ```

2. **Запустите скрипт**:
   Нажмите кнопку **"Рассчитать лучший ход"** на шахматной доске.

3. **Получите лучший ход**:
   Скрипт подсветит клетки с рекомендованным ходом.

## Требования 📋

- Шахматная доска с тегом `chess-board` или аналогичным.
- Поддержка загрузки внешних скриптов.

## Возможные проблемы 🚨

1. **Элемент отсутствует**:
   Убедитесь, что элемент `chess-board` есть на странице.

2. **Доска загружается позже**:
   Используйте `setInterval` для проверки наличия доски.

## Лицензия 📜

Проект с лицензией MIT. Свободное использование и модификация.
