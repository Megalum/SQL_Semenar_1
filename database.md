## DataBase = lesson1

USE lesson1;

![Error](database.png)

# Выведите название, производителя и цену для товаров, количество которых превышает 2

SELECT Manufacturer, Prise

FROM phone

WHERE ProductCount > 2;

![Error](Query1.png)

# Выведите весь ассортимент товаров марки “Samsung”

SELECT *

FROM phone

WHERE Manufacturer = "Samsung";

![Error](Query2.png)

# Выведите информацию о телефонах, где суммарный чек больше 100 000 и меньше 145 000

SELECT *

FROM phone

WHERE ProductCount * Prise > 100000 and ProductCount * Prise < 145000;

![Error](Query3.png)