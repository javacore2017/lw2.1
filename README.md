## lw2.1
**[25 баллов]** Реализовать программу SupermarketSimilator, которая имитирует работу супермаркета. Супермаркет работает определенное время, в течение которого туда приходят посетители случайным образом и случайным образом покупают товары. В конце работы должен выводиться отчет о продажах (статистика по проданным товарам). Покупатель кладет товары в корзину, затем встает в очередь на кассу, где ему выставляется счет, который может быть оплачен наличными, картой или бонусами, после оплаты покупатель покидает магазин. Покупатель не может купить товаров, больше чем реально есть в супермаркете. На определенные товары могут начисляться бонусы. Покупатель может принадлежать к различным категориям (Child - ребенок, Adult - взрослый, Retired - пенсионер). Детям нельзя продавать сигареты и алкоголь, пенсионерам могут быть скидки. Ассортимент товаров и их цены должны формироваться до открытия супермаркета. Товары могут продаваться по количеству или по весу.

Как минимум реализовать следующие сущности:
* Supermarket
* Customer
* Basket
* Product
* CashDesk - касса
* Report - отчет о работе
* Bill - счет на кассе
* PaymentMethod
* Discount

Программа должна логировать на консоль все события происходящие в супермаркете. Пример:

[time] Supermarket products have been formed:  
[product #1 details]  
[product #2 details]  
…  
[time] Supermarket is opened  
[time] New customer ‘customer#1’ arrived  
[time] Customer ‘customer#1’ picked up 2 units of milk  
…  
[time] Customer ‘customer#1’ at the cash desk, amount to pay: 1200   
[time] Customer paid 1200 by cash  
[time] Supermarket is closed  
[report]  
