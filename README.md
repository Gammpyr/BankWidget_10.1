# Bank Widget

## Описание:
Виджет для банка, разрабатываемый во время обучения языку Python.

## Основные функции, на данный момент:

[masks.py](src/masks.py)
1. `get_mask_card_number` - Принимает номер карты и возвращает его маску
2. `get_mask_account` - Принимает номер счета и возвращает маску формата **XXXX

[widget.py](src/widget.py)
1. `mask_account_card` - Определяет тип карты/счёта и возвращает соответствующую маску
2. `get_time` - Получает время и возвращает в формате ДД.ММ.ГГГГ

[processing.py](src/processing.py)
1. `filter_by_state` - возвращает новый список словарей,
    у которых ключ state соответствует указанному значению
2. `sort_by_date` - Возвращает новый список, отсортированный по дате

## Установка:

1. Клонируйте репозиторий:
```
git clone https://github.com/Gammpyr/BankWidget_10.1.git
```
2. Установите Poetry
```
pip install poetry

poetry init
```
3. Установите зависимости:
```
poetry install
```
