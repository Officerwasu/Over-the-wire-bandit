## Natas

#### Natas teaches the basics of serverside web-security.

Each level of natas consists of its own website located at http://natasX.natas.labs.overthewire.org, where X is the level number. There is no SSH login. To access a level, enter the username for that level (e.g. natas0 for level 0) and its password.

Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 and only readable by natas4 and natas5.

Start here:

Username: natas0

Password: natas0

URL:      http://natas0.natas.labs.overthewire.org



## Natas 0

Just view page source and you'll be able to see the password

![image](https://github.com/user-attachments/assets/8142c32c-8528-4f59-89ab-c2a3112e84ab)

password `0nzCigAq7t2iALyvU9xcHlYN4MlkIwlq `

## Natas 0-1

Just use ctrl+shift+i to inspect
![image](https://github.com/user-attachments/assets/e6ac6545-895f-4889-bd3f-896cb86afe3e)

password `TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI`

## Natas 1-2

![image](https://github.com/user-attachments/assets/fcad5295-c447-4102-a9c1-1d0445369e7d)

![image](https://github.com/user-attachments/assets/1be0f6a2-f9a6-4386-a823-6b5ea2dfa471)

password `3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH`

## Natas 2-3

In this level just check for the /robots.txt in the website
and we find s3cr3t directory is disallowed

![image](https://github.com/user-attachments/assets/5fa547f7-c80f-4c7f-95b9-1ec84d06a711)

password `QryZXc2e0zahULdHrtHxzyYkj59kUxLQ`

## Natas 3-4

you need to use a tool like burp suite or owasp zap to intercept the request and change the referer to natas5 

![image](https://github.com/user-attachments/assets/fc97d4d1-9fa6-4ee7-97a5-d6a6a3b7a54c)

![image](https://github.com/user-attachments/assets/c2929bde-17cd-446b-a18a-a2ae0fa2ba84)

password `0n35PkggAPm2zbEpOU802c0x0Msn1ToK`

## Natas 4-5




