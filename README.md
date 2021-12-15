# MIMIKEdgeClientContentCache

 MIMIKEdgeClientContentCache service library can help you interact with the following mimik services:

 * Content Cache

## Requirements
```
iOS 13.6+ device (simulators are not supported)

Working Content Caching Gateway. Please see the macOS setup instructions in the README-macOS-GATEWAY.md file.
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

## Example app on Test Flight
An example app showing the MIMIKEdgeClientContentCache library in action can be downloaded from a [Test Flight](https://testflight.apple.com/join/uLCPNxls) public link.

Please note that you will also have to setup a Content Caching Gateway on a macOS system. For Linux support, or any other questions please [contact mimik support](https://developer.mimik.com/support/)


## Author

mimik

```
https://github.com/mimikgit/cocoapod-MIMIKEdgeClientContentCache
```

## License

Edge is available under the MIT license. See the LICENSE file for more info.
