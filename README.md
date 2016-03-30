# ImageColors

[![CI Status](http://img.shields.io/travis/Robinson Presotto/ImageColors.svg?style=flat)](https://travis-ci.org/Robinson Presotto/ImageColors)
[![Version](https://img.shields.io/cocoapods/v/ImageColors.svg?style=flat)](http://cocoapods.org/pods/ImageColors)
[![License](https://img.shields.io/cocoapods/l/ImageColors.svg?style=flat)](http://cocoapods.org/pods/ImageColors)
[![Platform](https://img.shields.io/cocoapods/p/ImageColors.svg?style=flat)](http://cocoapods.org/pods/ImageColors)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

--

![alt tag](http://www.labvidas.com.br/robitto/github/imageColorsUpdated.png)

```ruby
UIImage.getColors({ (imageColors) -> Void in

    let primaryColor = imageColors.primaryColor
    let secondaryColor = imageColors.secondaryColor
    let backgroundColor = imageColors.backgroundColor
    let detailColor = imageColors.detailColor
    let allColors = imageColors.allColors

})
```

## Requirements

## Installation

ImageColors is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "ImageColors"
```

## Authors

Jathu Satkunarajah, @jathu (2015) (see [UIImageColors](https://github.com/jathu/UIImageColors))
Robinson Presotto, robipresotto@gmail.com (2016)

## License

ImageColors is available under the MIT license. See the LICENSE file for more info.
