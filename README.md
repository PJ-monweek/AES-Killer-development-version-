# AES Killer (Burp Suite Plugin - Development Version)
This project was developed with reference from [AES-Killer](https://github.com/Ebryx/AES-Killer) to support the decryption of more AES encrypted traffic on Burp Suite.

![Main AES Killer](https://user-images.githubusercontent.com/70949343/150760360-e182db42-cf51-4466-9a96-6d0c72e4a4a2.png)

### Requirements
* Burp Suite

### What it does
* The IProxyListener decrypt requests and encrypt responses, and an IHttpListener than encrypt requests and decrypt responses.
* Burp sees the decrypted traffic, including Repeater, Intruder and Scanner, but the client/mobile app and server see the encrypted version.

### AES Support
* ```AES/CBC/PKCS5Padding```
* ```AES/CBC/PKCS7Padding```
* ```AES/CFB8/NoPadding```
* ```AES/CFB8/PKCS7Padding```
* ```AES/CTR/PKCS5Padding```
* ```AES/CTR/PKCS7Padding```
* ```AES/ECB/PKCS5Padding```
* ```AES/ECB/PKCS7Padding```

### Format Support
* Base64
* Binary
* Hex

### How to Install
* Download jar file from [here](https://github.com/PJ-monweek/AES-Killer-development-version-/raw/master/AES%20Killer%20(development%20version).jar) and add in Burp Suite.
