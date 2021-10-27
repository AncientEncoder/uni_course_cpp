# Задача 3

## Реализовать текстовый вывод графа в файл в формате `JSON`

Доработать программу, чтобы она выводила созданный граф в файл в формате `JSON`.
Для этого вам нужно будет создать новую сущность:
```cpp
class GraphPrinter;
```
Который будет включать в себя всю логику по распечатке графа,
но не должен включать логику по работе с файлами, так как это не относится к его зоне ответственности.

Пример структуры (ключей и значений) выводимого файла:
```json
{
  "vertices": [
    {
      "id": 0,
      "edge_ids": [0, 1, 2]
    }, {
      "id": 1,
      "edge_ids": [0, 3, 4, 5]
    },
    "..."
  ],
  "edges": [
    {
      "id": 0,
      "vertex_ids": [0, 1]
    }, {
      "id": 1,
      "vertex_ids": [0, 2]
    },
    "..."
  ]
}
```

Можно в одну строку и даже без пробелов, как душе угодно, главное чтобы структура совпадала и `JSON` был валидный:
```json
{"vertices":[{"id":0,"edge_ids":[0,1,2]},"..."],"edges":[{"id":0,"vertex_ids":[0,1]},"..."]}
```

Пример файла можете посмотреть здесь: [graph.json](graph.json).

# Содержание `Pull Request`

- `*.cpp` и/или `*.hpp` исходные файлы.
- Скомпилированный бинарник.
- `graph.json` - результат выполнения программы.

# Рабочая директория:

`/02_knight_and_princess/name_surname/*`

# Время Выполнения

1 Недели

# Количество Баллов

10 Баллов

# Полезные ссылки:
- [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)
- [JSON](https://en.wikipedia.org/wiki/JSON)