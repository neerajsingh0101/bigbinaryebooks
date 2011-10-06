---
layout: credit_cards
title: Security
---

# PCI DSS compliancy

If a business transmits credit card data, then the business should be PCI DSS compliant. PCI stands for Payment Card Industry. DSS stands for Data Security Standard. PCI DSS is a security standard that sets policies and procedures for safeguarding the credit card information.

PCI DSS is not a law. However, failure to be PCI DSS compliant can be devastating to a business. If a business is not PCI DSS compliant the bank and credit card companies can levy a fine exceeding $100,000.00 in some cases. Also, no credit card processing company will do business with a business that is not PCI DSS compliant.

# How to Become PCI DSS Compliant

One should follow all general guidelines regarding the security of any web based applications. One should ensure that code is not vulnerable to sql injection, XSS attack and other malicious code.

* Always use SSL
* Do not store credit card numbers or CVV number in database.
* Ensure that credit card numbers and CVV numbers are not placed in any log in any format.

It is okay to store the last four digits of the credit card number in the database.

Many processing companies provide a hosted page which directly submits the information to the Gateway. In such cases, the credit card information does not even come to the application. This is an easy method to ensure that a business is PCI DSS compliant.


