1) Скрипт log_analyzer.py парсит логи nginx и создает отчет со статистикой

2) В скрипте test.py находятся функциональные тесты для log_analyzer.py

3) Скрипт log_analyzer.py можно запустить с параметром --config 
```python3 log_analyzer.py --config "Путь до файла"```

4)Логи бывают заархивированные и plain  

В отчет попадает:
  - количество URL запросов;
  - количество URL запросов в процентах от общего количества;
  - суммарное время запроса для URL;
  - суммарное время запроса для URL в процентах от общего количества;
  - среднее время запроса для URL;
  - максимальное время запроса для URL;
  - медианное время запроса для URL.
