# yii2-ecommerce-suite

Yii2 based engine for all-round e-commerce suite: sales, orders processing, affiliate program.

Live example: <http://alphatech.com.ua>

# Features

* Rich in modern marketing tools ("Black Friday", public & custom coupons; special cart discounts, last checkout step discounts, price break discounts etc.)
* Live calculation of shipping costs & fees (Nova Poshta, Ukr Poshta, Meest Express)
* SEO-first i18n (dynamic & url-based)
* Complete [Affiliate Program Engine](#Affiliate-Program-Engine)
* Модуль отзывов о товарах [^screen10005] [^screen10006] 
* модуль онлайн оплаты: Интеркасса, Onpay (возможна поддержка любых платёжных шлюзов) 
* гибкая настройка способов и методов доставки и выполнения заказа
* удобное оформление заказа [^screen10002] 
* очень гибкие системы акций, скидок и апсейлов [^screen10003] [^screen10004]

## Order Fulfillment

* Calculate and print labels for Nova Poshta [^screen10001]

## Marketing & Sales
* проект заточен под современные маркетинговые/ремаркетинговые коммуникации: начиная от "лайков" на страницах товаров, заканчивая функцией "поделиться моим заказом", который позволяет покупателям, после оформления заказа, поделиться им со своими друзьями. В связке с модулем "пригласи друга" и партнёрской программой, этот функционал поможет нарастить аудиторию вашего проекта
* [Refer a Friend](#Refer-a-Friend)
* гибкая система промо-акций (бесплатная доставка при покупке определенных товаров; скидки в зависимости от суммы заказа; скидочные купоны и пр.)
* поддержка динамических акций: начисление скидки пользователям, посетившим определённую страницу, или любые другие условия (реферал, наличие cookie и п.р.)
* модуль [Брошенных корзин](#Брошенные-корзины)
* модуль для проведения распродаж "Чёрная пятница" и пр. Живой пример: <http://alphatech.com.ua/blackfriday/> (когда акция не активна, на её странице посетители видят заглушку, форму для подписки на новости и дату начала следующей Чёрной Пятницы.

### Refer a Friend

У посетителей (регистрация не требуется) есть возможность пригласить друзей на сайт интернет-магазина - для каждого приглашения генерируется уникальная ссылка для отслеживания активности по кликам и продажам. Описание функционала на странице для посетителей:

> Вы приглашаете друзей, используя специальную форму на сайте и когда кто-то из ваших друзей оформит и оплатит заказ, вы получите бонус 500 грн на свой следующий заказ. Вашим друзьям не обязательно сразу же совершать покупки - мы запоминаем всех, кто переходит на сайт по вашим ссылкам и вы получите бонус, если ваш друг сделает заказ на сумму 950 грн (или больше) в течение 45 дней после того, как он воспользовался вашим приглашением в последний раз.

В данный момент посетители могут отправлять приглашения автоматически в Facebook, Вконтакте и по email адресам, а также генерировать прямые уникальные ссылки для использования в Twitter и пр.

Live example: <http://alphatech.com.ua/refer-friends/>

### Affiliate Program Engine

Полноценный движок партнёрской программы, подробнее: <https://github.com/Webkadabra/yii2-affiliate-program-engine>
Живой пример: <http://partners.alphatech.com.ua/>

### Брошенные корзины

В список брошенных корзин попадают только те "корзины", владелец которых не проявлял активности на сайте более 20 минут,
и для которых известен email или любой контактный телефон.

![](https://webkadabra.github.io/yii2-ecommerce-suite/screens/abandoned-carts.jpg)

# System Requirements

Works on standard LAMP/WAMP environments.

<center> <h1>Get it!</h1> </center>
                          
Contact me for a code & demo: <sergii@alphatech.com.ua>
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

