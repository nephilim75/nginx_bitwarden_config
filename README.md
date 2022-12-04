#### Requirements:

* config needs SSL certificates provided by Let's Encrypt
* created DH-parameter

<br>

## How to

#### Creating a DH-parameter
If you don't want to use the DH paramter provided by Let's Encrypt, you can create your own.

```
$ cd /path/to/CertificateLocation
$ openssl dhparam -out dhparam.pem 2048
```


#### Adapt config
Replce **sub.domain.tld** by your own domain you want to use.
