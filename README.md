# PEP Parse

PEP Parse - это веб-краулер на основе Scrapy, предназначенный для сканирования предложений по улучшению Python (PEPs) с официального сайта PEPs Python.

## Структура Проекта

crapy_parser_pep/
│
├── pep_parse/
│ ├── init.py
│ ├── items.py
│ ├── middlewares.py
│ ├── pipelines.py
│ ├── settings.py
│ └── spiders/
│ ├── init.py
│ └── pep.py
│
├── scrapy.cfg
├── requirements.txt
└── README.md

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yourusername/pep_parse.git
   cd pep_parse

2. Установите зависимости:
   ```bash
   pip install scrapy

## Использование
Для запуска паука и сканирования PEPs используйте следующую команду:
   ```bash
   scrapy crawl pep
   ```

## Вывод результатов
   
По завершении работы паука, результаты будут сохранены в папке results с именем файла, содержащим временную метку.



## Автор
[Nikita-Makkar](github.com/Nikita-Makkar)