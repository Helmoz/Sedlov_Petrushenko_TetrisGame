# Tetris Game

## Этапы разработки

- Этап 1 
    + Спроектирован класс Block
    + Созданны основные блоки игры
    + Реализованы методы получения рандомного блока
    + Реализована функция поворота блок
- Этап 1.5
    + Добавлена документация класса Block
- Этап 2
    + Все поля класса Block инкапсулированы в публичные свойства
    + Спроектирован класс Tetris, описаны основные поля класса
    + Реализованы базовые методы и созданы некоторые заготовки методов(не реализованы)
- Этап 3 
    + Реализованы заготовки из прошлой версии
    + Спроектированы и реализованы основные методы игры
    + Реализовано взаимодействие событий и их выполнение при игровых ситуациях
    + Все поля инкапсулированы в публичные свойства
- Этап 4
    + Реализован метод обработки нажатия клавиш
    + Написана документация для класса Tetris
- Этап 5
    + Написаны основные функции отрисовки объектов
    + Реализован процесс игры(пока что в Main)
    + Попытка написания мелодии из тетриса через Console.Beep
- Этап 6
    + Методы отрисовки выделены в отдельный класс Writer
    + Процесс игры выделен в класс GameCore
    + Убраны статические поля и методы
    + Убрана неудачная попытка написания мелодии

## Компоненты игры

**Предназначения классов**

- `Block` - класс фигуры тетриса,  каждая фигура хранится как двумерный массив. Получние рандомного блока, поворот по часовой стрелке
- `Tetris` - класс в котором описаны основные методы игры, взаиможействия объектов и их перемещение
- `GameCore` - класс, где создается объект тетриса, происходит инициализация полей, обработка нажатий, изменение скорости игры
- `Writer` - класс, отвечающий за отрисовку информации в начале/конце игры, а так же игрового поля, текущих очков и следующиего блока
- `Program` - создание объекта GameCore, запуск игры

## Авторы

 * [Седлов Лев](https://vk.com/helmoz17)
 * [Петрушенко Артур](https://vk.com/id193087953)

 
    

