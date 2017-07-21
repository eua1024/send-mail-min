# PHP minimal send mail
Send mail over PHP with minimal requirements from email services

Minimal requirements:
* Content-type
* Charset
* From
* MIME-Version
* Content-Transfer-Encoding
* Date
* Subject

Handle Subject field over iconv_mime_encode.