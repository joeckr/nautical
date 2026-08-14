## Nautical Dredge TODO

1. MVP

  - Able to indentify:
    - email
    - phone number
    - ipv4
    - ipv6
    - secrets
  - Replace identified values with token (IE: email -> EMAIL_1234)
  - Values are salted and hashed before storage
  - Store identified values in a database (Looking at BadgerDB by default)
  - Ability to restore identified values from the database
  - Ability to keep a persistent log of user access for restored values
  - Basic Auth to start

2. Other Auth methods

  - OIDC
  - SAML

3. Support Valkey for Data Storage at scale
