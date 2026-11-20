# ПСИМиАД, 4 курс — PySpark

| Срез | Работа | Папка |
|---|---|---|
| 1 | Самостоятельное задание по PySpark, **вариант 3** (пользовательские сессии из AVRO) | [`lab-pyspark/`](lab-pyspark/) |
| 2 | Самостоятельная работа по Spark MLlib | [`mllib/`](mllib/) |

Отчёт по каждой работе с описанием шагов и скриншотами лежит в `README.md` её папки.

## Окружение и запуск
- Python 3.14, PySpark 4.3.0 (`local[*]`), Java 17.
- `pip install pyspark jupyter`
- Для варианта 3 нужен модуль `spark-avro_2.13-4.3.0.jar`. Его можно положить в `$SPARK_HOME/jars` или подключить через `spark.jars.packages`.
- Ноутбуки запускаются из своей папки: `jupyter nbconvert --to notebook --execute zadanie-3.ipynb`.
