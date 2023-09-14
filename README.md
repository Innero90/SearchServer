# SearchServer

## Проект курса Яндекс Практикума "Разработчик С++"

SearchServer - поисковик документов с учетом минус-слов (документы с этими словами не учитываются в результатах поиска). Принцип работы приближен к поисковикам от больших IT- гигантов (Яндекс). 

## Основные функции:

- ранжирование результатов поиска по статистической мере TF-IDF;
- обработка стоп-слов (не учитываются поисковой системой и не влияют на результаты поиска);
- обработка минус-слов (документы, содержащие минус-слова, не будут включены в результаты поиска);
- создание и обработка очереди запросов;
- удаление дубликатов документов;
- постраничное разделение результатов поиска;
- возможность работы в многопоточном режиме;

## Использование:
Код покрыт тестами.
Тесты помогут разобраться в принципе работы.

## Системные требования

1. C++17 (STL)
2. GCC (MinGW-w64)


## Планы по доработке:
- Добавить возможность ввода документов с помощью файла.
- Реализовать графическое приложение, используя Qt.
