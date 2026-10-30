# SIAOD Labs

Репозиторий для лабораторных работ по дисциплине «Структуры и алгоритмы обработки данных».

## Исходный учебный репозиторий

Полная копия курса находится в каталоге [data-structures-and-algorithms/](data-structures-and-algorithms/README.md).

Источник: [mel0d1an/data-structures-and-algorithms](https://github.com/mel0d1an/data-structures-and-algorithms).

## Лабораторная работа № 1

Тема: анализ временной сложности элементарных алгоритмов.

- [Задание КИМ-01](data-structures-and-algorithms/M1-intro-and-basic-structures/kim-01-complexity-analysis.md)
- [Реализованный файл первой лабораторной](data-structures-and-algorithms/M1-intro-and-basic-structures/attachments/lab01-complexity-starter.py)
- [Методика воспроизводимых измерений](data-structures-and-algorithms/docs/reproducibility.md)
- [Методика верификации](data-structures-and-algorithms/docs/ai-verification.md)

Реализованы: сумма массива, поиск максимума, подсчёт равных пар двойным циклом и бинарное возведение в степень по модулю.

## Запуск

Из каталога data-structures-and-algorithms:

    python scripts/generate_data.py --variant 17 --only arrays
    python M1-intro-and-basic-structures/attachments/lab01-complexity-starter.py --variant 17

Номер варианта в командах выше — 17, ранее использовавшийся для этой лабораторной. Замеры и графики необходимо сформировать на своей машине: они зависят от среды выполнения.