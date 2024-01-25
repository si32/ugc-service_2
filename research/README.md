### Результаты исследования производительности хранилищ MongoDB и PostgreSQL

Из приведенный ниже результатов исследования можно сделать вывод, что хранилище MongoDB работает быстрее в несколько
раз, чем хранилище PostgreSQL на больших данных.

| Хранилище  | Получение количества лайков, сек. | Получения списка закладок, сек. | Добавление лайка, сек. | Удаление лайка, сек. |
|------------|-----------------------------------|---------------------------------|------------------------|----------------------|
| PostgreSQL | 0.21449                           | 0.20844                         | 0.00470                | 0.53177              |
| MongoDB    | 0.00199                           | 0.00118                         | 0.00117                | 0.00151              |