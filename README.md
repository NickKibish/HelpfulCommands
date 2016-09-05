# HelpfulCommands
Frequently usage commands

## APNS Certificate for Django
```bash
$ openssl pkcs12 -in pkey.p12 -out pkey.pem -nodes -clcerts
$ openssl pkcs12 -in cert.p12 -out cert.pem -nodes -clcerts
$ cat cert.pem pkey.pem > iphone_ck.pem
```
## Date Formatter
[Table with all formats](http://waracle.net/iphone-nsdateformatter-date-formatting-table/)
