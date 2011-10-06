---
layout: credit_cards
title: Buying Online
---

# Buying A Book Online

John is checking out the Amazon.com site and he wants to buy a book. At the checkout page he enters his credit card information and hits submit.

When he bought his coffee at Starbucks, the card reader read the credit card information, converting it in such a way that the information could be sent to the banking network.

When credit card information is accepted over the internet, then something equivalent of the "card reader" is needed which will convert the credit card number and other information to a data format that can be sent to the banking network. This is what Gateways do. Popular Gateways are [Authorize.net](http://www.authorize.net/),  [Braintree](http://www.braintreepayments.com/) and [Samurai](https://samurai.feefighters.com/).

In short, Gateways:

* Accept credit card information in a web friendly manner.
* Encode the information and then send it to the merchant bank.
* Once the response is received, they decode the response.
* They forward the response information to the web application that made the request through API.

