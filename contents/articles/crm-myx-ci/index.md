---
title: Improve xcode builds
author: hannes
company: CRM Factory (MCON)
date: 2016-03-15 00:00
template: article.jade
tags: Jenkins, fastlane, xcode
---

To sort our issues of building our Cordova apps for OSX I utilised the conecpt of [codesigning.guide][1] to create a better process of handling our certs, provisioning profiles and the app-build itself.  
[match][2] handles the certs and provisioning profiles, [gym][3] is building the ipa-file and [fastlane][4] is linking everything together and uploads the final build to HockeyApp.  

In the future we will be able to easily share certain profiles among the team members and lock others away oin a secure way.


[1]: https://codesigning.guide
[2]: https://github.com/fastlane/fastlane/tree/master/match
[3]: https://github.com/fastlane/fastlane/tree/master/gym
[4]: https://fastlane.tools
