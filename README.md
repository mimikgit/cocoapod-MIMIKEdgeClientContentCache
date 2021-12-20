# MIMIKEdgeClientContentCache

 MIMIKEdgeClientContentCache service library can help you interact with the following mimik services:

 * Content Cache

## Requirements
```
iOS 13.6+ device (simulators are not supported)

A working Content Caching Gateway.
```

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

## Video with more info
There is a short 5 minute video containing additional information available [on Vimeo](https://vimeo.com/658019639/79000e2f95). It explains how the Content Cache library, content caching gateway and content caching example application fit together.

## Author

mimik

```
https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache
```

## License

Edge is available under the MIT license. See the LICENSE file for more info.
