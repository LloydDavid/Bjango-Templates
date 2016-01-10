# Platform icon sizes

A comprehensive list of app icon sizes, including their screen pixel densities, uses and how they may be masked. The information below is intended to cover best practice for the current platform release version. I will do my best to keep everything up to date. Consult the vendor’s documentation if you have any concerns.

This is a living document, so please [get in touch](https://https://twitter.com/marcedwards/) if you notice any errors.

### Apple iOS
Masked: Yes, rounded corners.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 29×29 | 1× | Spotlight, Settings |

Full specs for iOS app icons can be found on [Apple’s developer site](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/IconMatrix.html#//apple_ref/doc/uid/TP40006556-CH27-SW1). [Mike Swanson’s iOS Rounded Rect Script](http://blog.mikeswanson.com/iosroundedrect) was used to create the icon masks for the Apple iOS templates.


Masked: No. Transparent areas are allowed.

|----------------|-----------------|------|
| 16×16 | 1× | Many places |
| 32×32 | 1×, 2× | Many places |
| 64×64 | 1×, 2× | Many places |
| 128×128 | 1×, 2× | Many places |
| 256×256 | 1×, 2× | Many places |
| 512×512 | 1×, 2× | Many places |
| 1024×1024 | 1×, 2× | Many places |

Full specs for OS X app icons can be found on [Apple’s developer site](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/Designing.html).


Masked: Yes, with subtle rounded corners.

|----------------|-----------------|------|
| 400×240 | 1× | Many places |

Full specs for tvOS app icons can be found on [Apple’s developer site](https://developer.apple.com/tvos/human-interface-guidelines/icons-and-images/).

Masked: Yes, to a circle.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 48×48 | 2× | Notification Center |
| 55×55 | 2× | Notification Center |
| 58×58 | 2× | iPhone |
| 80×80 | 2× | Long-Look, Home |
| 87×87 | 3× | iPhone |
| 88×88 | 2× | Long-Look |
| 172×172 | 2× | Short-Look |
| 196×196 | 2× | Short-Look |

Full specs for watchOS app icons can be found on [Apple’s developer site](https://developer.apple.com/watch/human-interface-guidelines/icons-and-images/).


Masked: No. Transparent areas are allowed.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 48×48 | 1× | Launcher and other places |
| 72×72 | 1.5× | Launcher and other places |
| 96×96 | 2× | Launcher and other places |
| 180×180 | 3× | Launcher and other places |
| 192×192 | 4× | Launcher and other places |
| 512×512 | Any or all | Google Play |

Full specs for Android app icons can be found on [Google’s developer site](https://www.google.com/design/spec/style/icons.html#icons-product-icons).

-----

Masked: No. Transparent areas are allowed.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 16×16 | Any or all | Many places |
| 32×32 | Any or all | Many places |
| 48×48 | Any or all | Many places |
| 256×256 | Any or all | Many places |

Full specs for Windows app icons can be found on [Microsoft’s developer site](https://msdn.microsoft.com/en-us/library/windows/desktop/dn742485(v=vs.85).aspx).

-----


Screen pixel densities: 1×, 1.25×, 1.5×, 2×, 4×.  
Masked: No.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 256×256 | Any or all | Many places | TODO! Info to come.

Full specs for Windows tiles can be found on [Microsoft’s developer site](https://msdn.microsoft.com/en-us/library/windows/apps/mt412102.aspx).



Screen pixel densities: 1×, 2×, and others.  
Masked: Often not masked. Sometimes rounded corners.

| Size in pixels | Pixel densities | Uses |
|----------------|-----------------|------|
| 16×16 | Any or all | Many places |
| 32×32 | Any or all | Many places |
| 144×144 | Any or all | Windows Tile icon |
| 152×152 | Any or all | iOS and Android |
| 180×180 | Any or all | iOS and Android |

[Audrey Roy Greenfeld’s Favicon Cheat Sheet](https://github.com/audreyr/favicon-cheat-sheet) is a great resource for web favicon sizes, as is [Wikipedia’s Favicon page](https://en.wikipedia.org/wiki/Favicon).