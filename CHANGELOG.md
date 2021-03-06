# Change Log

## 3.3.5 (2018/06/28)
* Removed requirement for the camera and calendar permissions. However, with these permissions enabled, you may be able to receive higher paying ads.

## 3.3.4 (2018/05/18)
* Added a new API to pass user consent as required for compliance with the European Union's General Data Protection Regulation (GDPR). If you are collecting consent from your users, you can make use of this new API to inform AdColony and all downstream consumers of the consent. Please see our [GDPR FAQ](https://www.adcolony.com/gdpr/) for more information and [our GDPR wiki](wiki/GDPR) for implementation details.
* Fixed a bug where advertisement video's close button was not easily tappable because of the status bar overlapping.
* Fixed a bug where unsafe access to the device's battery level was causing a crash.
* Several bug fixes and stability improvements.

## 3.3.0 (2018/01/12)
* Added Integral Ad Science (IAS) for viewability measurement.
* iPhoneX support
* Several bug fixes, memory usage optimizations, and stability improvements.

## 3.2.1 (2017/09/11)
* Fix for intermittent orientation issue discovered on iOS 11
* Fix for crash in ADCLogManager
* Misc bugfixes

## 3.2.0 (2017/08/24)
* iOS 11 compatibility along with several bugs fixes, stabilty and security improvements
* User experience improvements via enhanced skippability controls and a new mute/unmute feature
* Post-install events APIs
* Crash reporting and a new convenient test mode feature

## 3.1.1 (2017/03/29)
* Fix for intermittent orientation issue
* Fix for a small memory leak in AdColony browser
* Misc bugfixes

## 3.1.0 (2017/03/06)
* MOAT viewability support
* Internal viewable impression metrics
* Support for dashboard's play frequency zone setting
* Developers no longer required to pause/resume native ads
* AdColonyCompass library no longer available in public build
* Decreased compiled size of SDK
* Fix for crash causing JavaScriptCore to run out of memory
* Misc bugfixes

## 3.0.6 (2016/12/09)
* Reduced performance impact of JSON operations
* Reduced energy impact from internal update loop
* Misc bugfixes

## 3.0.5 (2016/11/10)
* Click event handler in AdColonyInterstitial
* User-left-application handler in AdColonyInterstitial
* Misc bugfixes

## 3.0.4 (2016/10/10)
* General Availability (GA) release
* Misc bugfixes

## 3.0.3 (2016/09/14)
* Vertical ads
* Flexible ad-orientation controls
* Updated Swift syntax in sample apps (requires Xcode 8)
* Increased deployment target to iOS 6.0
* Misc bugfixes

## 3.0.2 (2016/07/28)
* AdColony Compass™
* Native Ad Unit (InstantFeed™)
* In-app Purchase Promo (IAPP) ads
* Custom Messaging
* InstantFeed demo app
* Swift-based sample apps
* Misc bugfixes

## 3.0.1 (2016/05/19)
* Increased required Xcode version to 7.0
* Asynchronous API for making ad requests
* Delegate protocols replaced with block-based handlers
* Replaced usage of NSURLConnection with NSURLSession
* Optimized ad server communication protocols
* Video-playing APIs now take a reference to presenting view controller
* New APIs for option setting and configuring user metadata
