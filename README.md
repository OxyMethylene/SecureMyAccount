# SecureMyAccount

[![Build Status](https://travis-ci.org/games647/SecureMyAccount.svg?branch=master)](https://travis-ci.org/games647/SecureMyAccount)

Inspired by Github and Google, here is a Bukkit plugin to use two factor authentication. Your Mojang/Minecraft
account is protected by a single password or login token. What happens if your account gets stolen? Therefore this
plugin exists.

The password is time based and generated by your smartphone completely independent from your Mojang account and your
computer. This process is also known as 2FA.

## Features

* Protect selected commands
* Provides a better security to your server
* Displays the QR code on a minecraft map
* User friendly. They just need to scan the QR code with their smartphone
* A session will be valid for certain time period so you don't have to enter your password again.
* No other plugins required
* Free

## Commands

* /secureme - Requests a new secret key
* /session <code> - Starts a new session to prove your identity

## Permissions

* securemyaccount.command.request - Permission to invoke the request command
* securemyaccount.command.start - Permission to start a new session

## Images

![Ingame map QR code](http://i.imgur.com/9YuekuK.png)
![App code generation](http://i.imgur.com/HWNR8SK.png)

## Requirements

2 Factor App on your smartphone
For example:

#### Google Authenticator
* [Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)
* [IOS](https://itunes.apple.com/de/app/id388497605)

#### Duo Mobile
* [Windows (Phone)](https://www.microsoft.com/en-us/store/apps/duo-mobile/9nblggh08m1g)
* [IOS](https://itunes.apple.com/de/app/id422663827)
* [Android](https://play.google.com/store/apps/details?id=com.duosecurity.duomobile)

#### Authy
* [IOS](https://itunes.apple.com/de/app/id494168017)
* [Android](https://play.google.com/store/apps/details?id=com.authy.authy)

#### Microsoft Authenticator
* [Windows (Phone)](http://www.windowsphone.com/en-us/store/app/authenticator/e7994dbc-2336-4950-91ba-ca22d653759b)