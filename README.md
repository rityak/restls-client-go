# restls-client-go

Клиент restls.

Форк [metacubex/restls-client-go](https://github.com/metacubex/restls-client-go) для [miray](https://github.com/rityak/miray). Наш код — в ветке `miray`.

## Что изменено

- Аргументы `debugf` больше не вычисляются на каждой записи: это была гонка данных и лишние аллокации.
