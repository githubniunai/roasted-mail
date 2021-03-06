![Verify](https://github.com/andrepcg/roasted-mail/workflows/Verify/badge.svg)
[![Maintainability](https://api.codeclimate.com/v1/badges/ce6c6e92496cfd99b63e/maintainability)](https://codeclimate.com/github/andrepcg/roasted-mail/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/ce6c6e92496cfd99b63e/test_coverage)](https://codeclimate.com/github/andrepcg/roasted-mail/test_coverage)

![Roasted.email](roasted.png?raw=true "Roasted.email")

# Roasted.email

> Open-source Ruby on Rails app for disposable temporary emails.

See it live in:

- https://roasted.email
- https://ihave.buzz/
- https://needemail.top/
- https://iamno.monster/


## API

Roasted.email also provides a RESTful API to generate malboxes and read emails.

API defined using Swagger. [swagger/v1/swagger.yaml](swagger.yaml)

Read the docs live in https://roasted.email/api-docs

Mailbox generation capped at 15 requests every 24 seconds, around 1 request each 1.6 seconds.

## TODO

- [ ] Write better readme