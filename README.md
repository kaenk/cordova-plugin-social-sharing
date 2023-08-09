# PhoneGap / Cordova Social Sharing plugin

[![NPM version](https://img.shields.io/npm/v/community-cordova-plugin-social-sharing)](https://www.npmjs.com/package/community-cordova-plugin-social-sharing)
[![Downloads](https://img.shields.io/npm/dm/community-cordova-plugin-social-sharing)](https://www.npmjs.com/package/community-cordova-plugin-social-sharing)



#### This is a fork of the original plugin cordova-plugin-x-socialsharing

I dedicate a considerable amount of my free time to developing and maintaining many cordova plugins for the community ([See the list with all my maintained plugins][community_plugins]).
To help ensure this plugin is kept updated,
new features are added and bugfixes are implemented quickly,
please donate a couple of dollars (or a little more if you can stretch) as this will help me to afford to dedicate time to its maintenance.
Please consider donating if you're using this plugin in an app that makes you money,
or if you're asking for new features or priority bug fixes. Thank you!

[![](https://img.shields.io/static/v1?label=Sponsor%20Me&style=for-the-badge&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/eyalin)




> Version 6.0.0 is compatible with Android X. See [this issue](https://github.com/EddyVerbruggen/SocialSharing-PhoneGap-Plugin/pull/1039) for details. 5.6.8 is the last version before 6.0.0, so be sure to pick that if you run into Android X-related issues.

## 0. Index

1. [Description](#1-description)
2. [Screenshots](#2-screenshots)
3. [Installation](#3-installation)
4. [Usage on iOS and Android](#4-usage-on-ios-and-android)
5. [Web Share API](#5-web-share-api)
6. [Usage on Windows Phone](#6-usage-on-windows-phone)
7. [Share-popover on iPad](#7-share-popover-on-ipad)
8. [Whitelisting on iOS](#8-whitelisting-on-ios)
9. [NSPhotoLibraryUsageDescription on iOS](#9-nsphotolibraryusagedescription-on-ios)
10. [Import Types into an Ionic Angular Project](#10-import-types-into-an-ionic-angular-project)

## 1. Description

This plugin allows you to use the native sharing window of your mobile device.

* Share text, a link, a images (or other files like pdf or ics). Subject is also supported, when the receiving app supports it.
* Supports sharing files from the internet, the local filesystem, or from the www folder.
* You can skip the sharing dialog and directly share to Twitter, Facebook, or other apps.
* Compatible with [Cordova Plugman](https://github.com/apache/cordova-plugman).
* Officially supported by [PhoneGap Build](https://build.phonegap.com/plugins).

