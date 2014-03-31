# jQuery Email Address Validator by Mailgun

Given an arbitrary address, [Mailgun](http://www.mailgun.com) will validate the address based on:
* Syntax checks (RFC defined grammar)
* DNS validation
* Spell checks
* Email Service Provider (ESP) specific local-part grammar (if available)

## How to use the email validator on your form

1. Include jQuery
2. Include mailgun_validator.js
3. [Sign up](https://mailgun.com/signup) for a Mailgun account and insert your public API key
4. Attach mailgun_validator() function to the email field you want validated
5. Decide what should happen for valid emails, invalid emails and suggestions

## Demo

http://leemunroe.github.io/validator-demo/

## More information

* [Validator API Docs](http://documentation.mailgun.com/api-email-validation.html)
* [Mailgun Blog Announcement](http://blog.mailgun.com/post/free-email-validation-api-for-web-forms/)
