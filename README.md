# Elixir
An autodonation script for RotMG using the Paypal REST API.
# Requirements
* Business Account - Paypal
* http://www.codexworld.com/how-to/configure-paypal-auto-return-payment-data-transfer-business-account/ - Setup
* PhP server with access to your server database. Host it in the cloud, thugs.
* Mailclient to be used in success.php.

# Will not work without Auto-Return-Payment.
I have it setup as a level of verification that uses the product_id as the rank the user is being set to. If you request, I can edit it for gold, etc. Adding another rank is pretty easy, etc. I don't have auto recurring payments setup yet.
# IPN isn't setup, add it and it could be more secure. If I get around to it, I'll add IPN.
Used alot of google resources, thanks codex and other resources who walked me through using the REST API. 