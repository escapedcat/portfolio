---
title: VWNMS VRent booking app v2
author: hannes
company: CRM Factory (MCON)
date: 2015-04-01 00:00
template: article.jade
tags: Cordova, Jenkins, Xcode, gulp
---

In the second phase of [the project][3] I focused on frontend ops, CI and deployment. Using xcode to manually create builds for iOS apps can take up a lot of time. I utilized gulp to create multiple tasks to handle the setup and build of the app via [Cordova][1]. From nothing to a downloadable app on [HockeyApp][2] without any manual work.

[1]: https://cordova.apache.org
[2]: http://hockeyapp.net
[3]: https://www.crm-factory.eu/case-studies/webapps-ecommerce-case-studies/vrent-a-premium-corporate-carsharing-platform-for-web-mobile-and-tablets