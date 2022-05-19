# Перечень тестируемых сценариев
### Предусловия:
* Авторизованным пользователем перейти во вкладку "Создать заказ"
* Заполнить обязательные поля валидными данными
## Поле "Подъезд"
* Ввод существующего значения в поле Подъезд
1. Заполнить поле Подъезд номером "2"
2. Нажать "Запустить заказ"

**Ожидаемый результат: Заказ создается, данные сохраняются**

**Фактический результат: Заказ создается, данные сохраняются**

* Изменение сохраненного значения в поле Подъезд
1. Перейти во вкладку мои заказы
2. Выбрать свой, недаавно сформированный, заказ
3. Заполнить поле Подъезд номером отличным от сохраненного значением
4. Нажать "Сохранить изменения"

**Ожидаемый результат: Данные сохраняются**

**Фактический результат: Данные сохраняются**

* Ввод пробела перед значением
1. Заполнить поле Подъезд номером "2", поставив пробел перед номером
2. Нажать "Запустить заказ"

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Ввод пробела в середине значением
1. Заполнить поле Подъезд номером "11" поставив пробел между единицами
2. Нажать "Запустить заказ"

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Ввод пробела после значением
1. Заполнить поле Подъезд номером "2" поставив пробел после номера
2. Нажать "Запустить заказ""

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Отправка формы с пустым полем 
1. Оставить поле Подъезд пустым
2. Нажать заупстить заказ

**Ожидаемый результат: Данные обрабатываются и сохраняются, ошибки нет**

**Фактический результат: Данные обрабатываются и сохраняются, ошибки нет**

## Поле "Этаж"
* Ввод существующего значения в поле Этаж
1. Заполнить поле Этаж номером "10"
2. Нажать "Запустить заказ"

**Ожидаемый результат: Заказ создается, данные сохраняются**

**Фактический результат: Заказ создается, данные сохраняются**
* Ввод этажа со знаком "-"
1. Заполнить поле Этаж номером "-1"
2. Нажать "Запустить заказ"

**Ожидаемый результат: Заказ создается, данные сохраняются**

**Фактический результат: Заказ создается, данные сохраняются**

* Изменение сохраненного значения в поле Этаж
1. Перейти во вкладку мои заказы
2. Выбрать свой, недаавно сформированный, заказ
3. Заполнить поле Этаж номером отличным от сохраненного значением
4. Нажать "Сохранить изменения"

**Ожидаемый результат: Данные сохраняются**

**Фактический результат: Данные сохраняются**

* Ввод пробела перед значением
1. Заполнить поле Этаж номером "2", поставив пробел перед номером
2. Нажать "Запустить заказ"

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Ввод пробела в середине значением
1. Заполнить поле Этаж номером "11" поставив пробел между единицами
2. Нажать "Запустить заказ"

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Ввод пробела после значением
1. Заполнить поле Этаж номером "2" поставив пробел после номера
2. Нажать "Запустить заказ""

**Ожидаемый результат: Данные обрабатываются и сохраняются, пробелы автоматически опускаются**

**Фактический результат: Данные обрабатываются и сохраняются, пробелы не опускаются**

* Отправка формы с пустым полем
1. Оставить поле Этаж пустым
2. Нажать заупстить заказ

**Ожидаемый результат: Данные обрабатываются и сохраняются, ошибки нет**

**Фактический результат: Данные обрабатываются и сохраняются, ошибки нет**

## Поле комментарий Отправитель

* Увелечение поля комментарий в высоту
1. Перейти во вкладку Доп информация
2. Ввести комментарий, превышающий длину строки

**Ожидаемый результат: Данные вводятся, поле увеличивается в высоту**

**Фактический результат: Данные вводятся, поле не увеличивается в высоту**

* Отмена данных клавишей Х
1. Перейти во вкладку Доп информация
2. Ввести любой комментарий(больше 200 символов)
3. Удалить комментарий клавишей в правом углу поля "Х"

**Ожидаемый результат: Данные удаляются, клавиша не "едет" во время ввода комменатрия**

**Фактический результат: Данные удаляются, расположение клавиши "едет"**

* Отправка пустого поля
1. Перейти во вкладку Доп информация
2. Оставить поле пустым

**Ожидаемый результат: Заказ запускается, ошибки нет**

**Фактический результат:  Заказ запускается, ошибки нет**

* Редактирование значения
1. Зайти во вкладку Мои заказы
2. Выбрать, недавно оформленный, заказ
3. Нажать Редактировать
4. Перейти во вкладку Доп информация
5. Изменить значение комментария на новое
6. Нажать Сохранить изменения

**Ожидаемый результат: Данные сохраняются**

**Фактический результат: Данные сохраняются**

* Отправка комментария из одного символа
1. Перейти во вкладку Доп информация
2. Ввести комментарий из одного символа

**Ожидаемый результат: Данные сохраняются, заказ запускается**

**Фактический результат: Данные сохраняются, заказ запускается**

* Отправка длинного комментария(более 500 символов)
1. Перейти во вкладку Доп информация
2. Ввести комментарий, превышающий 500 символов

**Ожидаемый результат: Данные сохраняются, заказ запускается**

**Фактический результат: Данные сохраняются, заказ запускается**
  

## Поле комментарий Получатель
* Увелечение поля комментарий в высоту
1. Перейти во вкладку Доп информация
2. Ввести комментарий, превышающий длину строки

**Ожидаемый результат: Данные вводятся, поле увеличивается в высоту**

**Фактический результат: Данные вводятся, поле увеличивается в высоту**

* Отмена данных клавишей Х
1. Перейти во вкладку Доп информация
2. Ввести любой комментарий(больше 200 символов)
3. Удалить комментарий клавишей в правом углу поля "Х"

**Ожидаемый результат: Данные удаляются, клавиша не "едет" во время ввода комменатрия**

**Фактический результат: Данные удаляются, расположение клавиши "едет"**

* Отправка пустого поля
1. Перейти во вкладку Доп информация
2. Оставить поле пустым

**Ожидаемый результат: Заказ запускается, ошибки нет**

**Фактический результат:  Заказ запускается, ошибки нет**

* Редактирование значения
1. Зайти во вкладку Мои заказы
2. Выбрать, недавно оформленный, заказ
3. Нажать Редактировать
4. Перейти во вкладку Доп информация
5. Изменить значение комментария на новое
6. Нажать Сохранить изменения

**Ожидаемый результат: Данные сохраняются**

**Фактический результат: Данные сохраняются**

* Отправка комментария из одного символа
1. Перейти во вкладку Доп информация
2. Ввести комментарий из одного символа

**Ожидаемый результат: Данные сохраняются, заказ запускается**

**Фактический результат: Данные сохраняются, заказ запускается**

* Отправка длинного комментария(более 500 символов)
1. Перейти во вкладку Доп информация
2. Ввести комментарий, превышающий 500 символов

**Ожидаемый результат: Данные сохраняются, заказ запускается**

**Фактический результат: Данные сохраняются, заказ запускается**
  




