# Drupal-Clean
A clean install of Drupal to be used for patching contrib modules.

## Run automated test
Ssh into the container and run the test:
```
lando ssh
phpunit --filter testCheckoutWithPaymentAmountMismatch web/modules/contrib/commerce_stripe/tests/src/FunctionalJavascript/CheckoutTest.php
```
