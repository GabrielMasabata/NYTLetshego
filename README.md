# NYT
IOS Test - NY Times Most Popular Articles Assessment 

## Description
Simple app to hit the NY Times Most Popular Articles API and show a list of articles, that shows details when items on the list are tapped (a typical master/detail app).
The fasted way i could think to develop the app was to have as minimal tasks to do as possible and that included: 
* designing the table view controller using code,
* minimalistic design of the launch screen using the storyboard,
* separating the API call into models so it runs only when called,
* use of user defaults to store downloaded data,
* network check using one function,
* using map function instead of segues

https://developer.nytimes.com/

Topic demoestrate in this application
---
##### * Structure - Network Connection and API Connection
##### * MVP Model of how data is retrieved via the API, displayed in the app's two different screens.
##### * Apple UX Simple Code Design for Articles Page and UI Design for More Info on each Arctivle Page
####  * TableView Controller Code Design
####  * Data Storage -  Realm
---
## Environment
---
Xcode Version 11.3.1 (11C504)
```
## Tools And Resources Used
---
- [CocoaPods](https://cocoapods.org/) - CocoaPods is a dependency manager for Swift and Objective-C Cocoa projects. It has over 33 thousand libraries and is used in over 2.2 million apps. CocoaPods can help you scale your projects elegantly.
- [fastlane](https://docs.fastlane.tools/) - The easiest way to automate building and releasing your iOS and Android apps.
- [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.

## Library Used
- [Alamofire].
- [MBProgressHUD].
- [SDWebImage].
- [ObjectMapper].
- [RealmSwift].
- [SwiftyUserDefaults].
- [ObjectMapper+Realm].


# Installation
* Installation by cloning the repository and Unziping it
* Go to directory
* Open terminal, pod install.
* NYTimesLetshego.xcworkspace
* use command + B or Product -> Build to build the project
* Press run icon in Xcode or command + R to run the project on Simulator.
