UITextFieldAccessories
============

A simple pod that adds accessory buttons to a UITextField keyboard toolbar. There is a "Clear" button that clears the text, a "Done" button that dismisses the keyboard, and an option "+/-" button that toggles a negative sign for numerical entries. The last one is particularly helpful when used with number pad keyboard, which don't have a negative sign button.

## Usage

First, import the pod in the View Controller you want to use it with.
```swift
import UITextFieldAccessories
```
You can now add the accessories to any UITextField:
```swift
myTextField.addAccessory(addPlusMinus: true)
```

## Installation

UITextFieldAccessories is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'UITextFieldAccessories'
```

## Requirements:

- CocoaPods 1.0.0+

## Author

michael-s-wu, michael_s_wu@yahoo.com

## License

UITextFieldAccessories is available under the MIT license. See the LICENSE file for more info.
