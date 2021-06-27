# VNDTextField

The numbers that the user enters in the field are automatically formatted to display in the VNĐ amount format.

## Demo

![Alt text](https://github.com/ios-lib/VNDTextField/blob/main/image/demo.png "Demo") 


## Installation

**Source files**

Add new swift package by link: 
https://github.com/ios-lib/VNDTextField

Or clone this repository or download it in zip-file. Then you will find source files under InputTextField directory. Copy them to your project.

## Usage


Import InputTextField and add it programatically to your view or add UITextField in your Storyboard, and then change the custom class to TextField

![Alt text](https://github.com/SunPencil/CPTextField/blob/main/ImageDemo/ImportTextField.png "Custom class")

```swift
@IBOutlet weak var myTextfield: TextField!
 
 myTextfield.setButtonBackGroundColor(backgroudColor: .darkGray)
 myTextfield.setButtonCornerRadius(cornerRadius: 10)
```


## License

InputTextField is released under the MIT license.


