# RippleEffect

https://user-images.githubusercontent.com/86227924/191195810-51c1dc7c-0e0c-44fe-a55d-c9b72b96678c.mov

As in iOS is not a native behaviour, to create the Ripple Effect like Material Design with UIKit we have this following approach.

* Create UIView extension to add Ripple Effect through a tap gesture

* Create a rounded Shape Layer with expand and fade effect

* Make the effect starts on the tap gesture’s location

# Usage

```` swift
// With no color. Default color will be gray:
someView.addRippleEffect()

// With a custom color:
someView.addRippleEffect(.red)
