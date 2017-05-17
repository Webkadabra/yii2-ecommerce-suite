# yii2-ecommerce-suite

> (ру) PHP/MySql движок интернет-магазина на Yii 2: имея в наличии наш код, PHP/Yii разработчики могут создавать интернет-магазины "под ключ" в течение очень короткого времени.
> (en) Yii2 based engine for all-round e-commerce suite: sales, orders processing, affiliate program.

Рабочий пример: <http://alphatech.com.ua>

# Фичи

* автоматический подсчёт стоимости пересылки груза перевозчиками Новая Почта (Нова Пошта); Мист Экспресс; Деливери-авто; **Укрпочта** (Укрпошта)
* удобный интерфейс для обработки заказов
* мультиязычность (по-уомлчанию для фронтенда перевод происходит на стороне клиента; из коробки поддержка английского, русского и украинского языков)
* [Партнёрская программа](#Партнёрская-программа)
* модуль онлайн оплаты: Интеркасса, Onpay (возможна поддержка любых платёжных шлюзов) 
* гибкая настройка способов и методов доставки и выполнения заказа
* удобное оформление заказа

## Процессинг заказов

* Печать всех необзодимых форм для отправки посылок Укр Поштой (форма 116)
* генерация и печать документации для отправки заказов перевозчиком Новая Почта[^screen10001]

## Маркетинг
* проект заточен под современные маркетинговые/ремаркетинговые коммуникации: начиная "лайками" на странице товаров заканчивая функцией "поделиться моим заказом", который позволяет покупателям, после оформления заказа, поделиться им со своими друзьями. В связке с модулем "пригласи друга" и партнёрской программой, этот функционал поможет нарастить аудиторию вашего проекта
* модуль акций [Пригласи Друга](#Пригласи-Друга)
* гибкая система промо-акций (бесплатная доставка при покупке определенных товаров; скидки в зависимости от суммы заказа; скидочные купоны и пр.)
* модуль [Брошенных корзин](#Брошенные-корзины)
* модуль для проведения распродаж "Чёрная пятница" и пр. Живой пример: <http://alphatech.com.ua/blackfriday/> (когда акция не активна, на её странице посетители видят заглушку, форму для подписки на новости и дату начала следующей Чёрной Пятницы.

### Пригласи Друга

У посетителей (регистрация не требуется) есть возможность пригласить друзей на сайт интернет-магазина - для каждого приглашения генерируется уникальная ссылка для отслеживания активности по кликам и продажам. Описание функционала на странице для посетителей:

> Вы приглашаете друзей, используя специальную форму на сайте и когда кто-то из ваших друзей оформит и оплатит заказ, вы получите бонус 500 грн на свой следующий заказ. Вашим друзьям не обязательно сразу же совершать покупки - мы запоминаем всех, кто переходит на сайт по вашим ссылкам и вы получите бонус, если ваш друг сделает заказ на сумму 950 грн (или больше) в течение 45 дней после того, как он воспользовался вашим приглашением в последний раз.

В данный момент посетители могут отправлять приглашения автоматически в Facebook, Вконтакте и по email адресам, а также генерировать прямые уникальные ссылки для использования в Twitter и пр.

Живой пример: <http://alphatech.com.ua/refer-friends/>

### Партнёрская программа
Живой пример: <http://partners.alphatech.com.ua/>

### Брошенные корзины

В список брошенных корзин попадают только те "корзины", владелец которых не проявлял активности на сайте более 20 минут,
и для которых известен email или любой контактный телефон.

![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/abandoned-carts.jpg)

---

## Галерея скриншотов

[^screen10001]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/order-fulfill-novaposhta.png)


