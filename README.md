Sweego Bridge
=============

Provides Sweego integration for Symfony Mailer.

Configuration example:

```env
# SMTP
MAILER_DSN=sweego+smtp://LOGIN:PASSWORD@HOST:PORT
```

where:
 - `LOGIN` is your Sweego SMTP login
 - `PASSWORD` is your Sweego SMTP password
 - `HOST` is your Sweego SMTP host
 - `PORT` is your Sweego SMTP port

```env
# API
MAILER_DSN=sweego+api://API_KEY@default
```

where:
 - `API_KEY` is your Sweego API Key

Sponsor
-------

This bridge for Symfony 7.2 is [backed][1] by [Sweego][2] itself!

Sweego is a European email and SMS sending platform for developers and product builders.
Easily create, deliver, and monitor your emails and notifications.

Help Symfony by [sponsoring][3] its development!

Resources
---------

 * [Contributing](https://symfony.com/doc/current/contributing/index.html)
 * [Report issues](https://github.com/symfony/symfony/issues) and
   [send Pull Requests](https://github.com/symfony/symfony/pulls)
   in the [main Symfony repository](https://github.com/symfony/symfony)

[1]: https://symfony.com/backers
[2]: https://www.sweego.io/
[3]: https://symfony.com/sponsor
