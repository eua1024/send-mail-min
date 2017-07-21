# PHP minimal send mail
Send mail over PHP with minimal requirements from email services

## Minimal requirements from email services:
1. Header fields:
	* Content-type
	* Charset
	* From
	* MIME-Version
	* Content-Transfer-Encoding
	* Date
	* Subject
2. Handle Subject field of header over [iconv_mime_encode](http://php.net/manual/en/function.iconv-mime-encode.php).