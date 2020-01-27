# BankZecure Web Application

All the instructions are in the quest!

The fake customer accounts' credentials are listed [here](https://github.com/WildCodeSchool/quest-springboot-sql-injection/blob/master/FakeAccountsCredentials.md).

## Vulnerability

A hacker can tamper with the `identifier` field. During profile update, setting the hidden form field `identifier` to the value of another customer results in overwriting and/or viewing the data of the other customer. Imho the code is too primitive to fix this.