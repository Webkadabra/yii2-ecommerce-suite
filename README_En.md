# yii2-ecommerce-suite

Yii2 based engine for all-round e-commerce suite: sales, orders processing, affiliate program.

Live example: <http://alphatech.com.ua>

# Features

* Rich in modern marketing tools ("Black Friday", public & custom coupons; special cart discounts, last checkout step discounts, price break discounts etc.)
* Live calculation of shipping costs & fees (Nova Poshta, Ukr Poshta, Meest Express)
* SEO-first i18n (dynamic & url-based)
* Complete [Affiliate Program Engine](#Affiliate-Program-Engine)
* Reviews module [^screen10005] [^screen10006] 
* Payment gateways, COD payments and direct transfer payments 
* Custom and rich shipping/fulfillment settings
* Tested and fine-tuned checkout process [^screen10002] 
* Powerful promotions, discounts and upsales [^screen10003] [^screen10004]

## Order Fulfillment

* Calculate and print labels for Nova Poshta [^screen10001]
* SMS notifications for clients (tracking, payment info) 

## Marketing & Sales
* проект заточен под современные маркетинговые/ремаркетинговые коммуникации: начиная от "лайков" на страницах товаров, заканчивая функцией "поделиться моим заказом", который позволяет покупателям, после оформления заказа, поделиться им со своими друзьями. В связке с модулем "пригласи друга" и партнёрской программой, этот функционал поможет нарастить аудиторию вашего проекта
* [Refer a Friend](#Refer-a-Friend)
* гибкая система промо-акций (бесплатная доставка при покупке определенных товаров; скидки в зависимости от суммы заказа; скидочные купоны и пр.)
* поддержка динамических акций: начисление скидки пользователям, посетившим определённую страницу, или любые другие условия (реферал, наличие cookie и п.р.)
* [Abandoned Carts](#Abandoned-Carts) module
* "Black Friday" sale module. Live example: <http://alphatech.com.ua/blackfriday/> (when event has passed there is a fallback page with email collecting form)

### Refer a Friend

Powerful marketing tool! Any visitor (registration is not required) can invite firends and get bonus when referred friend makes a verified purchase. Customers identified by email. 

Visitors can invite firends via Facebook, VK, email and by simply sending their unique invite links via Twitter, Skype etc.

Live example: <http://alphatech.com.ua/refer-friends/>

### Affiliate Program Engine

Complete affiliate program engine, details: <https://github.com/Webkadabra/yii2-affiliate-program-engine>
Live example: <http://partners.alphatech.com.ua/>

### Abandoned Carts

Send a reminder to any customer who has forgotten to complete order checkout: 
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

