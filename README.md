# UIFloatLabelTextField
### A subclassed UITextField that implements the Float Label UI design pattern. 
___

### About
In 2013, [Matt D. Smith](http://twitter.com/mds) unveiled the **Float Label** user interface design pattern. In short, it retains a text field's placeholder above said text field as a *floating label*. This label is brightly colored when the field is active, and dimly colored when a user has finished editing that field. 

I also want to credit [Jared Verdi](http://twitter.com/jverdi) for developing the first iOS implementation of this pattern in his [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) project. I used it as a reference to make this version, but executed many aspects differently. I also added a few other features that I personally needed, and plan on enhancing this library overtime.

![Sample Gif of Library in Action](http://d13yacurqjgara.cloudfront.net/users/6410/screenshots/1254439/form-animation-_gif_.gif)

### Changelog (v1.0.1)
- Float label no longer hugs the top edge when visible
- Float label now appears if text field is pre-populated

### Features
- Works with all `NSTextAlignments`
- Works with all view `init` styles
	- Visual Formatting Language (for programmatic NSAutoLayout)
	- Manual Frame Initialization
	- Storyboards and Xibs
- Support for disabling all default UIMenuController options
	- Paste, Copy, Cut, Select, Select All
- Animations
	- UILabel animation for toggling UILabel visibility
	- Animation for clearing text

### Installation
```
pod 'UIFloatLabelTextField'
```

### Usage
Check out `UIFloatLabelTextField.h` for a full list of editable properties. Also, check out the **UIFloatLabelSampleApp** for an example impementation of the application.

### Created and maintained by
[Arthur Ariel Sabintsev](http://www.sabintsev.com/) 

### LICENSE
Please refer to the **LICENSE** file.
