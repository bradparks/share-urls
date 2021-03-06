# share-urls
Collection of share urls and documentations of various share urls


## Android Intents
- [Official Documentation](https://developer.chrome.com/multidevice/android/intents)
- [Paul Kinlan](https://paul.kinlan.me/)
  - [Launch App from Web with Fallback](https://paul.kinlan.me/launch-app-from-web-with-fallback/)
  - [Sharing natively on Android from the Web](https://paul.kinlan.me/sharing-natively-on-android-from-the-web/)
- [Intent URI Description](http://stackoverflow.com/questions/23231589/intent-anchor-syntax-description)
 - [How do I pass Parameters?](http://stackoverflow.com/questions/16738276/how-do-i-pass-parameters-to-android-intent-in-new-scheme-on-chrome)
- [Security](http://www.mbsd.jp/Whitepaper/IntentScheme.pdf) 


## iOS
- [iPhoneURLScheme Reference](https://developer.apple.com/library/ios/featuredarticles/iPhoneURLScheme_Reference/Introduction/Introduction.html)
- [launching your own application via a custom url scheme](http://iosdevelopertips.com/cocoa/launching-your-own-application-via-a-custom-url-scheme.html)
- [iPhone URL Scheme Reference](http://www.rcconsulting.com/Downloads/Apple_iPhone_URL_Scheme_Reference.pdf)
- [Iphone URL Schemes](http://wiki.akosma.com/IPhone_URL_Schemes)
- [Handle Open Url](http://handleopenurl.com/)
- [URL Schemes for iOS and Android](http://fokkezb.nl/2013/09/20/url-schemes-for-ios-and-android-2/)
- [Offline Web App with data uri](http://www.sensefulsolutions.com/2010/01/iphone-offline-web-app-creator-data-uri.html)
    
## sms: URIs
- [SMS URIs](http://weblog.west-wind.com/posts/2013/Oct/09/Prefilling-an-SMS-on-Mobile-Devices-with-the-sms-Uri-Scheme)
- [iOS sms:](https://developer.apple.com/library/ios/featuredarticles/iPhoneURLScheme_Reference/SMSLinks/SMSLinks.html#//apple_ref/doc/uid/TP40007899-CH7-SW1)


## Custom Protocol Handling 
- [Protocol Handlers](https://developer.mozilla.org/en/docs/Web-based_protocol_handlers)
- [Compatability](http://caniuse.com/#search=registerProtocolHandler)

## whatsapp 
- [Official Documentation](https://www.whatsapp.com/faq/en/iphone/23559013)

### Sending a message to a specific contact:
- [Stack Overflow](http://stackoverflow.com/questions/21500570/start-whatsapp-from-url-href-with-custom-text-content)
```
<a href="intent://send/<<number here>>#Intent;scheme=smsto;package=com.whatsapp;action=android.intent.action.SENDTO;end">
```

[Whatsapp Manifest](https://gist.github.com/kimenye/eef321a2a182bd4544af) (Look for `BROWSABLE`)

### most simple ios fallback
Link with `href="tel:+905555555555"`. Tell the user to click -> add to contacts.

## Twitter Web Intents
https://dev.twitter.com/web/intents


## Paypal Payment Links
- [Stack Overflow](http://stackoverflow.com/questions/9956081/how-can-i-create-a-paypal-link-that-will-send-money-to-a-specific-e-mail-address)
  - Assuming you are logged in: [POC](https://www.paypal.com/us/cgi-bin/webscr?cmd=_send-money&nav=1&email=FOO@BAR.com)
- [Link Generator](http://www.blogbyben.com/2009/04/paypal-link-generator-build-your-own-1.html)
  - Seems to work without need to be logged in






## Skype URIs 
- [Official Documentation](https://msdn.microsoft.com/en-us/library/office/dn745883.aspx)



