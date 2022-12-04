## Requirements:

* config needs SSL certificates provided by Let's Encrypt
* created DH-parameter

## Creating a DH-parameter

```
$ cd /path/to/CertificateLocation
$ openssl dhparam -out dhparam.pem 2048
```
