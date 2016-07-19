# ZProgressHUD
ZProgressHUD is a simple HUD for swift.

# Installation
## CocoaPods
<CocoaPods.org> is a dependency manager for Cocoa Projects.
``` bash 
use_frameworks!

pod 'ZProgressHUD', '~> 0.0.4’
```
then
``` bash 
run pod install 
```

## Manual

``` bash 
1. Download this project, And drag ZProgressHUD.xcodeproj to your own project.
2. In your target’s General tab, click the ’+’ button under Linked Frameworks and Libraries.
3. Select the ZProgressHUD.framework to Add to your platform. 
```

# Usage 

#### provide class function to use.

``` swift
public class func show(status: String? = nil)
public class func showError(status: String? = nil)
public class func showInfo(status: String? = nil)
public class func showSuccess(status: String? = nil)
public class func showStatus(status: String) 
public class func showImage(image: UIImage? = nil, status: String? = nil)
public class func dismiss(delay: NSTimeInterval = 0.0)
public class func isVisible() -> Bool
```

the swift 3.0 refrence the list interface.
``` swift 
public class func show(_ status: String? = nil)
public class func show(image: UIImage?, status: String? = nil) 
public class func show(error status: String?)
public class func show(info status: String?)
public class func show(success status: String?)
public class func show(status: String)
public class func dismiss(_ delay: TimeInterval = 0.0)
public class func isVisible() -> Bool
#### provide  class function to set HUD
``` 

``` swift
public class func setDefaultStyle(style: ZProgressHUDStyle)
public class func setDefaultProgressType(progressType: ZProgressHUDProgressType)
public class func setDefaultMaskType(maskType: ZProgressHUDMaskType)
public class func setDefaultPositionType(positionType: ZProgressHUDPositionType)
public class func setLineWidth(width: CGFloat)
public class func setMinmumSize(size: CGSize)
public class func setCornerRadius(radius: CGFloat)
public class func setFont(font: UIFont)
public class func setErrorImage(image: UIImage?)
public class func setSuccessImage(image: UIImage?)
public class func setInfoImage(image: UIImage?)
public class func setForegroundColor(color: UIColor?)
public class func setBackgroundColor(color: UIColor?)
public class func setBackgroundLayerColor(color: UIColor?)
public class func setStatus(status: String?)
public class func setCenterOffset(offset: UIOffset)
public class func resetCenterOffset()
public class func setMinimumDismissDuration(duration: NSTimeInterval)
public class func setFadeInAnimationDuration(duration: NSTimeInterval)
public class func setFadeOutAnimationDuration(duration: NSTimeInterval)
```

the swift 3.0 refrence the list interface.
``` swift
public class func setDefault(style: ZProgressHUDStyle)
public class func setDefault(progressType: ZProgressHUDProgressType)
public class func setDefault(maskType: ZProgressHUDMaskType)
public class func setDefault(positionType: ZProgressHUDPositionType)
public class func setLineWidth(_ width: CGFloat)
public class func setMinmumSize(_ size: CGSize)
public class func setCornerRadius(_ radius: CGFloat)
public class func setFont(_ font: UIFont)
public class func setErrorImage(_ image: UIImage?)
public class func setSuccessImage(_ image: UIImage?)
public class func setInfoImage(_ image: UIImage?)
public class func setForegroundColor(_ color: UIColor?)
public class func setBackgroundColor(_ color: UIColor?)
public class func setBackgroundLayerColor(_ color: UIColor?)
public class func setStatus(_ status: String?)
public class func setCenterOffset(_ offset: UIOffset)
public class func resetCenterOffset()    
public class func setMinimumDismissDuration(_ duration: TimeInterval)
public class func setFadeInAnimationDuration(_ duration: TimeInterval)
public class func setFadeOutAnimationDuration(_ duration: TimeInterval)
```
