# MyLib

[![CI Status](https://img.shields.io/travis/hautran96/MyLib.svg?style=flat)](https://travis-ci.org/hautran96/MyLib)
[![Version](https://img.shields.io/cocoapods/v/MyLib.svg?style=flat)](https://cocoapods.org/pods/MyLib)
[![License](https://img.shields.io/cocoapods/l/MyLib.svg?style=flat)](https://cocoapods.org/pods/MyLib)
[![Platform](https://img.shields.io/cocoapods/p/MyLib.svg?style=flat)](https://cocoapods.org/pods/MyLib)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

MyLib is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'MyLib'
```

```ruby
pod install
```
# Usage

```ruby
let builder = IstorageBuilder().setApiKey(ApiKey: "ApiKey").build()
```

## GetFile 

```ruby
  builder.getFile(key: fileKey, success: { (data) in
            //thành công
            print(data!)
        }) { (data, response, error) in
            //error
        }
```

## upload

```ruby
    builder.upLoad(imageURL: imageURL , success: { (data) in
                print(data!)
            }) { (data,response, error) in
                print(data!)
                print(response!)
    }
```

## Author

hautran96, haut5918@gmail.com

## License

MyLib is available under the MIT license. See the LICENSE file for more info.
