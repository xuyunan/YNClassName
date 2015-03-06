# YNClassName
Display ViewContrller's Class Name on Screen

![image](./Screenshot.png) 

# Usage
```objective-c
#import "UIViewController+ClassName.h"

- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {
    // Override point for customization after application launch.
    [UIViewController displayClassName:YES];
    return YES;
}
```
