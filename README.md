# Xcode-Objective-C-Code-Snippets

### Class
- `cd(class declaration)`
```objc
@interface <#class name#> : <#superclass#>

@end
```

- `ce(class extension)`
```objc
@interface <#class name#> ()

@end
```

- `ci(class implementation)`
```objc
@implementation <#class#>

<#methods#>

@end
```

- `cc(class category)`
```objc
@interface <#class name#> (<#category name#>)

@end
```

- `cci(class category implementation)`
```objc
@implementation <#class#> (<#category name#>)

<#methods#>

@end
```

### protocol

### property

### Method Function
### UIViewController
### UIView
### IBAction
### LazyLoad
### pragma
- `hpm`
```objc
#pragma mark - 
```
- `hpmgetter`
```objc
#pragma mark - Getter
```
- `hpmsetter`
```objc
#pragma mark - Setter
```
### import
- `hiu`
```objc
#import "<#header#>"
```
- `his`
```objc
#import <<#header#>>
```
### define
- `hdm`
```objc
#define macro <##>
```
### typedef
- `tdblock`
```objc
typedef <#void#>(^<#BlockName#>)(<#void#>);
```
- `tdnsenum`
```objc
typedef NS_ENUM(NSInteger, <#Type#>) {
    <#Type1#> = 0,
    <#Type2#>,
};
```
- `tdenum`
```objc
typedef enum {
    <#Type1#> = 0,
    <#Type2#>,
}<#Type#>;
```
- `tdnsoptions`
```objc
typedef NS_OPTIONS(NSUInteger, <#Type#>) {
    <#Type1#> = 0,
    <#Type2#> = 1 << 0,
    <#Type3#> = 1 << 1,
};
```
### GCD
### UITableView
### UITableViewItemsKit
### UICollectionView
### Notification
- `cnca`
```objc
[[NSNotificationCenter defaultCenter] addObserver:self selector:@selector(<#selector#>:) name:<#name#> object:nil];
```
- `cncpo`
```objc
[[NSNotificationCenter defaultCenter] postNotificationName:<#NSNotificationName#> object:<#nil#>];
```
- `cncpou`
```objc
[[NSNotificationCenter defaultCenter] postNotificationName:<#NSNotificationName#> object:<#nil#> userInfo:<#nil#>];
```
- `cncr`
```objc
[[NSNotificationCenter defaultCenter] removeObserver:self];
```
- `fnc`
```objc
- (void)<#method#>:(NSNotification *)notification {
    <#statements#>
}
```
### KVO
- `ckvoa`
```objc
[<#instance#> addObserver:<#self#> forKeyPath:<#KeyPath#> options:NSKeyValueObservingOptionNew | NSKeyValueObservingOptionOld context:<#nil#>];
```
- `ckvor`
```objc
[self removeObserver:self forKeyPath:<#KeyPath#>];
```
- `fkvo`
```objc
- (void)observeValueForKeyPath:(NSString *)keyPath ofObject:(id)object change:(NSDictionary *)change context:(void *)context {
    if ([keyPath isEqualToString:<#KeyPath#>]) {
        <#statements#>
    }
}
```
### NSUserDefault
### block
- `cbkd`
```objc
<#returnType#>(^<#blockName#>)(<#parameterTypes#>) = ^(<#parameters#>) {
    <#statements#>
};
```
- `cbke`
```objc
!self.<#block#> ? : self.<#block#>(<##>);
```
### delegate
- `cdelegatee`
```objc
if ([<#self.delegate#> respondsToSelector:@selector(<#method#>)]) {
    [<#self.delegate#> <#method#>];
}
```
### AssociatedObject
- `faotemplate`
```objc
- (<#id#>)<#propertyName#> {
    return objc_getAssociatedObject(self, _cmd);
}
- (void)set<#PropertyName#>:(<#id#>)<#propertyName#> {
    objc_setAssociatedObject(self, @selector(<#propertyName#>), <#propertyName#>, <#OBJC_ASSOCIATION_#>);
}
```
### Other

