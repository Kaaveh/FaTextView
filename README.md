# FaTextView

This library helps you to show english number in persian even if your persian font doesn't have persian number.

[![](https://jitpack.io/v/Kaaveh/FaTextView.svg)](https://jitpack.io/#Kaaveh/FaTextView)
## Example
Use it like regular `TextView` :

```XML
<ir.kaaveh.faview.FaTextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="سلام دنیا 123"
    ... />
```
It's be like this:

<img src="https://github.com/Kaaveh/FaTextView/blob/master/screens/demo.png" height="150"/><br>

## Setup
1. Add it in your root build.gradle at the end of repositories:
```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
2. Add the dependency
```
dependencies {
        implementation 'com.github.Kaaveh:FaTextView:1.0'
}
```
3. Enjoy!
