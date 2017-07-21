# PHP minimal send mail
Send mail over PHP with minimal requirements from email services

## Minimal requirements from email services:
Headers fields:
* Content-type
* Charset
* From
* MIME-Version
* Content-Transfer-Encoding
* Date (in format `Fri, 21 Jul 2017 18:05:32 +0200 (CEST)`)
* Subject (handle this field over [iconv_mime_encode](http://php.net/manual/en/function.iconv-mime-encode.php))