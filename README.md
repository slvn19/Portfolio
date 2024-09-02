# <a name="up" />Портфолио 

Ниже приведены примеры использования освоенных в ходе обучения инструментов и составленной тестовой документации.
Раздел в стадии редактрования.

[Тестирование веб (чек-листы, тест-кейсы, баг-репорты)](#test-design)<br>
[Тестирование API (Postman)](#api-testing)<br>

## <a name="test-design" /> Тестирование веб (чек-листы, тест-кейсы, баг-репорты)

### 1. Чек-лист и баг-репорты для строки поиска сайта Vinyl.ru 

![Image alt](https://github.com/slvn19/Portfolio/blob/main/pv_vinyl.ru.jpg)

**Чек-лист**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/cl_vinyl.ru.jpg)

**Баг-репорт 1**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br1_vinyl.ru.jpg)

**Баг-репорт 2**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br2_vinyl.ru.jpg)

**Баг-репорт 3**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br3_vinyl.ru.jpg)

**Баг-репорт 4**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br4_vinyl.ru.jpg)

**Баг-репорт 5**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br5_vinyl.ru.jpg)

**Баг-репорт 6**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br6_vinyl.ru.jpg)

**Баг-репорт 7**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br7_vinyl.ru.jpg)

**Баг-репорт 8**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br8_vinyl.ru.jpg)

**Баг-репорт 9**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/br9_vinyl.ru.jpg)

---

### 2. Чек-лист и тест-кейсы для строки поиска на главной странице ozon.ru

![Image alt](https://github.com/slvn19/Portfolio/blob/main/pv_ozon.ru.jpg)

**Чек-лист**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/cl_ozon.ru.jpg)

**Тест-кейс 1**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc1_ozon.ru.jpg)

**Тест-кейс 2**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc2_ozon.ru.jpg)

**Тест-кейс 3**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc3_ozon.ru.jpg)

**Тест-кейс 4**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc4_ozon.ru.jpg)

**Тест-кейс 5**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc5_ozon.ru.jpg)

**Тест-кейс 6**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc6_ozon.ru.jpg)

**Тест-кейс 7**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/tc7_ozon.ru.jpg)

---

### 3. Чек-лист и баг-репорты для окна параметров генерируемого изображения (простой цвет) сервиса Dummy images generator (https://www.websiteplanet.com/ru/webtools/dummy-images-generator/)

![Image alt](https://github.com/slvn19/Portfolio/blob/main/dig_pv.jpg)

**Чек-лист**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/dig_cl1.jpg)
![Image alt](https://github.com/slvn19/Portfolio/blob/main/dig_cl2.jpg)

**Баг-репорт 1**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br1.jpg)

**Баг-репорт 2**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br2.jpg)

**Баг-репорт 3**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br3.jpg)

**Баг-репорт 4**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br4.jpg)

**Баг-репорт 5**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br5.jpg)

**Баг-репорт 6**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br6.jpg)

**Баг-репорт 7**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br7.jpg)

**Баг-репорт 8**

![Image alt](https://github.com/slvn19/Portfolio/blob/16a9fcfe57c2e59b5aca5722970a3279e6acf0d6/dig_br8.jpg)

---

## <a name="api-testing" /> Тестирование API (Postman)

Данная коллекция представляет собой набор запросов для тестового API (https://restful-booker.herokuapp.com/), имитирующего сервис бронирования отеля. В коллекции реализованы запись генерируемого запросом "Create auth token" токена и id последней созданной записи (запрос CreateBooking) в переменные коллекции и дальнейшее их применение. В запросах PUT, PATCH, DELET используется авторизация по ранее сгенерированному токену, сохраненному в переменных коллекции.

Коллекция: https://github.com/slvn19/Portfolio/blob/main/Restful%20Booker.postman_collection.json

**Список запросов**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/pm1.jpg)

**Использование токена авторизации**

![Image alt](https://github.com/slvn19/Portfolio/blob/main/pm2.jpg)
![Image alt](https://github.com/slvn19/Portfolio/blob/main/pm3.jpg)
![Image alt](https://github.com/slvn19/Portfolio/blob/main/pm4.jpg)
