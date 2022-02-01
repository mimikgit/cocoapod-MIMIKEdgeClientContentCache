# MIMIKEdgeClientContentCache

 MIMIKEdgeClientContentCache service library can help you interact with the following mimik services:

 * Content Cache

## Requirements
```
iOS 13.6+ device (simulators are not supported)

A working Content Caching Gateway.
```

 using these API functions:

 * `contentReferences`
 * `contentReferenceFor`
 * `deleteContentReferenceFor`
 * `addContentReferenceFor`

 Please see the in-code documentation in Xcode for more details.

## Installation

To install it, simply add the following lines to your Podfile:

```swift
platform :ios, '13.6'
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/mimikgit/cocoapod-edge-specs.git'
```

For Xcode 13.2.x compatibility

```swift
pod 'MIMIKEdgeClientContentCache', '~> 13.2.1'
```

## Content Caching Gateway Setup

Please see the Content Caching Gateway setup instructions for macOS in [README-Content-Caching-Gateway-Setup-macOS](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache/blob/main/README-Content-Caching-Gateway-Setup-macOS.md)

For Linux support or any other questions please [contact mimik support](https://developer.mimik.com/support/)

## Content Caching Example application on Test Flight
A content caching example app showing the [MIMIKEdgeClientIdentity](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientIdentity) library in action can be downloaded from this [Test Flight](https://testflight.apple.com/join/uLCPNxls) public link. You will need to open the link on an iOS device.

You can find out more about the example application in [README-Example-App-Test-Flight](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache/blob/main/README-Example-App-Test-Flight.md)

Please note that in order to use the example application you will have setup a Content Caching Gateway as described here: [Requirements](#Requirements).

## Video with more information
There is a short 5 minute video containing additional information available [on Vimeo](https://vimeo.com/658019639/79000e2f95). It explains how the Content Cache library, content caching gateway and content caching example application fit together.

## Tutorial

Visit this [tutorial](https://devdocs.mimik.com/tutorials/03-index) to learn more about the mimik client library and how to integrate it into your iOS project.

## mimik client and service libraries

Don't forget to checkout all mimik client and service libraries [available on Github](https://github.com/search?q=cocoapod-MIMIKEdgeClient)

Direct links:
 
 * [MIMIKEdgeClient](https://github.com/mimikgit/cocoapod-MIMIKEdgeClient)
 
 * [MIMIKEdgeClientIdentity](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientIdentity)
 * [MIMIKEdgeClientProfile](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientProfile)
 * [MIMIKEdgeClientPeer](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientPeer)
 * [MIMIKEdgeClientThumbnail](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientThumbnail)
 
 * [MIMIKEdgeClientAssessment](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientAssessment)
 * [MIMIKEdgeClientNotification](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientNotification)
 * [MIMIKEdgeClientTracker](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientTracker)
 * [MIMIKEdgeClientContentCache](https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache)

## Author

mimik

```
https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache
```

## License

The aforementioned mimik client and service libraries are available under the MIT license. See the LICENSE file for more information.
