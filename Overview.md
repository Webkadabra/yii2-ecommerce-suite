---
layout: default
title: Движок для интернет-магазина на PHP и Yii2
permalink: /
---

# [yii2-ecommerce-suite](https://webkadabra.github.io/yii2-ecommerce-suite)

[CLICK HERE FOR ENGLISH VERSION](https://webkadabra.github.io/yii2-ecommerce-suite/README_En)

> PHP/MySql движок интернет-магазина на Yii 2: имея в наличии наш код, PHP/Yii разработчики могут создавать интернет-магазины "под ключ" в течение очень короткого времени.


Рабочий пример: <http://alphatech.com.ua>

# Фичи и модули

* Уникальный модуль динамических блоков для главной страницы
* Автоматический подсчёт стоимости пересылки груза перевозчиками Новая Почта (Нова Пошта); Мист Экспресс; Деливери-авто; **Укрпочта** (Укрпошта)
* Удобный интерфейс для обработки заказов
* Мультиязычность (по-умолчанию для фронтенда перевод происходит на стороне клиента; из коробки поддержка английского, русского и украинского языков)
* Полноценная [Партнёрская программа](#партнёрская-программа)
* Модуль отзывов о товарах [^screen10005] [^screen10006] 
* Модуль онлайн оплаты: Интеркасса, Onpay (возможна поддержка любых платёжных шлюзов) 
* Гибкая настройка способов и методов доставки и выполнения заказа
* Удобное оформление заказа [^screen10002] 
* Очень гибкие системы акций, скидок и апсейлов [^screen10003] [^screen10004]
* Управление содержимым сайта с версионированием (историей изменений) страниц, позволяет создавать уникальные посадочные страницы
* Модуль "Блог" (пример: http://alphatech.com.ua/blog/)

## Процессинг заказов

* Печать всех необходимых форм для отправки посылок Укр Поштой (форма 116)
* Генерация и печать документации для отправки заказов перевозчиком Новая Почта[^screen10001]
* СМС уведомления/счета/напоминания об оплате для клиентов

## Маркетинг
* Проект заточен под современные маркетинговые/ремаркетинговые коммуникации: начиная от "лайков" на страницах товаров, заканчивая функцией "поделиться моим заказом", который позволяет покупателям, после оформления заказа, поделиться им со своими друзьями. В связке с модулем "пригласи друга" и партнёрской программой, этот функционал поможет нарастить аудиторию вашего проекта
* Модуль акций [Пригласи Друга](#Пригласи-Друга)
* Гибкая система промо-акций (бесплатная доставка при покупке определенных товаров; скидки в зависимости от суммы заказа; скидочные купоны и пр.)
* Поддержка динамических акций: начисление скидки пользователям, посетившим определённую страницу, или любые другие условия (реферал, наличие cookie и п.р.)
* Бесплатная доставка при заказе определённых товаров (с ограничениями по минимальной сумме заказа)
* Модуль [Брошенных корзин](#Брошенные-корзины)
* Модуль для проведения распродаж "Чёрная пятница" и пр. Живой пример: <http://alphatech.com.ua/blackfriday/> (когда акция не активна, на её странице посетители видят заглушку, форму для подписки на новости и дату начала следующей Чёрной Пятницы.

### Пригласи Друга

У посетителей (регистрация не требуется) есть возможность пригласить друзей на сайт интернет-магазина - для каждого приглашения генерируется уникальная ссылка для отслеживания активности по кликам и продажам. Описание функционала на странице для посетителей:

> Вы приглашаете друзей, используя специальную форму на сайте и когда кто-то из ваших друзей оформит и оплатит заказ, вы получите бонус 500 грн на свой следующий заказ. Вашим друзьям не обязательно сразу же совершать покупки - мы запоминаем всех, кто переходит на сайт по вашим ссылкам и вы получите бонус, если ваш друг сделает заказ на сумму 950 грн (или больше) в течение 45 дней после того, как он воспользовался вашим приглашением в последний раз.

В данный момент посетители могут отправлять приглашения автоматически в Facebook, Вконтакте и по email адресам, а также генерировать прямые уникальные ссылки для использования в Twitter и пр.

Живой пример: <http://alphatech.com.ua/refer-friends/>

### Партнёрская программа

Полноценный движок партнёрской программы, подробнее: <https://github.com/Webkadabra/yii2-affiliate-program-engine>
Живой пример: <http://partners.alphatech.com.ua/>

### Брошенные корзины

В список брошенных корзин попадают только те "корзины", владелец которых не проявлял активности на сайте более 20 минут,
и для которых известен email или любой контактный телефон.

![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/abandoned-carts.jpg)

# Технические требования

Система работает на стандартном LAMP/WAMP сервере.

# ДЕМО ВЕРСИЯ

Хотите попробовать продукт перед покупкой? Закажите бесплатную демо-версию:

<script type="text/javascript" src="//gama.mautic.net/form/generate.js?id=6"></script>
                          
<devkadabra@gmail.com>
---

## Галерея скриншотов

[^screen10001]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/order-fulfill-novaposhta.png)
[^screen10002]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/checkout-shipping.jpg)
[^screen10003]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/cart-suammry.jpg)
[^screen10004]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/cart-upsale.jpg)
[^screen10005]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/reviews-list.jpg)
[^screen10006]: ![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/reviews-post.jpg)

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-34726674-8', 'auto');
  ga('send', 'pageview');

</script>
