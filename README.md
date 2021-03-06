# VNDTextField

The numbers that the user enters in the field are automatically formatted to display in the VNĐ amount format.

## Demo

<img src="https://github.com/ios-lib/VNDTextField/blob/main/image/demo.png" width="200">


## Installation

**Source files**

Add new swift package by link: 
Xcode -> File -> Swift packages -> Add package Dependency... and parse this link:

https://github.com/ios-lib/VNDTextField

Or clone this repository or download it in zip-file. Then you will find source files under InputTextField directory. Copy them to your project.

## Usage

Sample here:
https://github.com/ios-lib/VNDDemo/tree/main

Import VNDTextField and add it programatically to your view or add UITextField in your Storyboard, and then change the custom class to TextField

![Alt text](https://github.com/ios-lib/VNDTextField/blob/main/image/ImportTextField.png "Custom class")

```swift
import VNDTextField

@IBOutlet weak var myTextfield: VNDTextField!
 
 myTextfield.setButtonBackGroundColor(backgroudColor: .darkGray)
 myTextfield.setButtonCornerRadius(cornerRadius: 10)
```

## Athor

Create by:   [SunPencil](https://github.com/SunPencil/)

website:     [codetoanbug.com](https://codetoanbug.com/)


## License

[VNDTextField is released under the MIT license.](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)




