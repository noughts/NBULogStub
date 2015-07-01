# NBULogStub

[![CI Status](http://img.shields.io/travis/Koichi Yamamoto/NBULogStub.svg?style=flat)](https://travis-ci.org/Koichi Yamamoto/NBULogStub)
[![Version](https://img.shields.io/cocoapods/v/NBULogStub.svg?style=flat)](http://cocoapods.org/pods/NBULogStub)
[![License](https://img.shields.io/cocoapods/l/NBULogStub.svg?style=flat)](http://cocoapods.org/pods/NBULogStub)
[![Platform](https://img.shields.io/cocoapods/p/NBULogStub.svg?style=flat)](http://cocoapods.org/pods/NBULogStub)

自作 pod で NBULog を使いたいときに、cocoapods 0.36.0 以降だと正常に $ pod repo push できなくなりました。
公式ドキュメントに掲載されている方法 https://github.com/CyberAgent/NBULog をまとめて pod にしたものです。

Podfile には pod "NBULog"、pod spec には s.dependency "NBULogStub" を追加し、
podライブラリのヘッダ部に #import <NBULogStub.h> を追加しましょう。

また、NBULogVerbose などのレベルが低いログを表示するには [NBULog setKitLogLevel:DDLogLevelVerbose] しておきましょう。


## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

NBULogStub is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "NBULogStub"
```

## Author

Koichi Yamamoto, noughts@gmail.com

## License

NBULogStub is available under the MIT license. See the LICENSE file for more info.
