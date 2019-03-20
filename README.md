# Xcode-Objective-C-Code-Snippets

## Path

```
~/Library/Developer/Xcode/UserData/CodeSnippets
```

## Code-Snippets

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
- `pd`
```objc
@protocol <#protocol name#> <NSObject>

<#methods#>

@end
```

- `cdelegatee`
```objc
if ([<#self.delegate#> respondsToSelector:@selector(<#method#>)]) {
    [<#self.delegate#> <#method#>];
}
```

### property

- `passign`
```objc
@property (nonatomic, assign) <#ObjectType#> <#property#>;
```

- `pcopy`
```objc
@property (nonatomic, copy) <#ObjectType#> *<#property#>;
```

- `pstrong`
```objc
@property (nonatomic, strong) <#ObjectType#> *<#property#>;
```

- `pweak`
```objc
@property (nonatomic, weak) <#ObjectType#> *<#property#>;
```

- `pblock`
```objc
@property (nonatomic, copy) <#void#>(^<#property#>)(<#void#>);
```

- `pdelegate`
```objc
@property (nonatomic, weak) id <<#ObjectType#>> <#delegate#>;
```

- `pnsinteger`
```objc
@property (nonatomic, assign) NSInteger <#property#>;
```

- `pnsuinteger`
```objc
@property (nonatomic, assign) NSUInteger <#property#>;
```

- `pcgfloat`
```objc
@property (nonatomic, assign) CGFloat <#property#>;
```

- `pfloat`
```objc
@property (nonatomic, assign) float <#property#>;
```

- `pdouble`
```objc
@property (nonatomic, assign) double <#property#>;
```

- `pint`
```objc
@property (nonatomic, assign) int <#property#>;
```

- `plong`
```objc
@property (nonatomic, assign) long <#property#>;
```

- `plonglong`
```objc
@property (nonatomic, assign) long long <#property#>;
```

- `pbool`
```objc
@property (nonatomic, assign) BOOL <#property#>;
```

- `pcgsize`
```objc
@property (nonatomic, assign) CGSize <#property#>;
```

- `pcgrect`
```objc
@property (nonatomic, assign) CGRect <#property#>;
```

- `pcgpoint`
```objc
@property (nonatomic, assign) CGPoint <#property#>;
```

- `pstring`
```objc
@property (nonatomic, copy) NSString *<#property#>;
```

- `parray`
```objc
@property (nonatomic, copy) NSArray *<#property#>;
```

- `pdictionary`
```objc
@property (nonatomic, copy) NSDictionary *<#property#>;
```

- `pmstring`
```objc
@property (nonatomic, strong) NSMutableString *<#property#>;
```

- `pmarray`
```objc
@property (nonatomic, strong) NSMutableArray *<#property#>;
```

- `pmdictionary`
```objc
@property (nonatomic, strong) NSMutableDictionary *<#property#>;
```

- `pgarray`
```objc
@property (nonatomic, copy) NSArray <<#ObjectType#>>*<#property#>;
```

- `pgdictionary`
```objc
@property (nonatomic, copy) NSDictionary <<#ObjectType#>, <#ObjectType#>>*<#property#>;
```

- `pgmarray`
```objc
@property (nonatomic, strong) NSMutableArray <<#ObjectType#>>*<#property#>;
```

- `pgmdictionary`
```objc
@property (nonatomic, strong) NSMutableDictionary <<#ObjectType#>, <#ObjectType#>>*<#property#>;
```

- `pibtv`
```objc
@property (weak, nonatomic) IBOutlet UITableView *<#tableView#>;
```
- `pibcv`
```objc
@property (weak, nonatomic) IBOutlet UICollectionView *<#collectionView#>;
```

- `pibsv`
```objc
@property (weak, nonatomic) IBOutlet UIScrollView *<#scrollView#>;
```

- `pibview`
```objc
@property (weak, nonatomic) IBOutlet UIView *<#name#>View;
```

- `pibcontrol`
```objc
@property (weak, nonatomic) IBOutlet UIControl *<#name#>Control;
```

- `piblabel`
```objc
@property (weak, nonatomic) IBOutlet UILabel *<#name#>Label;
```

- `pibbutton`
```objc
@property (weak, nonatomic) IBOutlet UIButton *<#name#>Button;
```

- `pibtextfield`
```objc
@property (weak, nonatomic) IBOutlet UITextField *<#name#>TextField;
```

- `pibtextview`
```objc
@property (weak, nonatomic) IBOutlet UITextView *<#name#>TextView;
```

- `pibimageview`
```objc
@property (weak, nonatomic) IBOutlet UIImageView *<#name#>ImageView;
```

- `puivc`
```objc
@property (nonatomic, strong) UIViewController *<#viewController#>;
```

- `puitv`
```objc
@property (nonatomic, strong) UITableView *<#tableView#>;
```

- `puicv`
```objc
@property (nonatomic, strong) UICollectionView *<#collectionView#>;
```

- `puisv`
```objc
@property (nonatomic, strong) UIScrollView *<#scrollView#>;
```

- `puiview`
```objc
@property (nonatomic, strong) UIView *<#name#>View;
```

- `puicontrol`
```objc
@property (nonatomic, strong) UIControl *<#name#>Control;
```

- `puilabel`
```objc
@property (nonatomic, strong) UILabel *<#name#>Label;
```

- `puibutton`
```objc
@property (nonatomic, strong) UIButton *<#name#>Button;
```

- `puitextfield`
```objc
@property (nonatomic, strong) UITextField *<#name#>TextField;
```

- `puitextview`
```objc
@property (nonatomic, strong) UITextView *<#name#>TextView;
```

- `puiimageview`
```objc
@property (nonatomic, strong) UIImageView *<#name#>ImageView;
```

- `puicolor`
```objc
@property (nonatomic, strong) UIColor *<#name#>Color;
```

- `puiimage`
```objc
@property (nonatomic, strong) UIImage *<#name#>Image;
```

### method & function

- `fni`
```objc
- (<#void#>)<#method#> {
    <#statements#>
}
```

- `fnc`
```objc
+ (<#void#>)<#method#> {
    <#statements#>
}
```

- `finit`
```objc
- (instancetype)init {
    self = [super init];
    if (self) {
        <#statements#>
    }
    return self;
}
```

- `fdealloc`
```objc
- (void)dealloc {
    <#statements#>
}
```

- `finitwithframe`
```objc
- (instancetype)initWithFrame:(CGRect)frame {
    self = [super initWithFrame:frame];
    if (self) {
        <#statements#>
    }
    return self;
}
```

- `finitwithcoder`
```objc
- (instancetype)initWithCoder:(NSCoder *)coder {
    self = [super initWithCoder:coder];
    if (self) {
        <#statements#>
    }
    return self;
}
```

- `finitwithstyle`
```objc
- (instancetype)initWithStyle:(UITableViewCellStyle)style reuseIdentifier:(NSString *)reuseIdentifier {
    self = [super initWithStyle:style reuseIdentifier:reuseIdentifier];
    if (self) {
        <#statements#>
    }
    return self;
}
```

- `finitwithnibname`
```objc
- (instancetype)initWithNibName:(NSString *)nibNameOrNil bundle:(NSBundle *)nibBundleOrNil {
    self = [super initWithNibName:nibNameOrNil bundle:nibBundleOrNil]
    if (self) {
        <#statements#>
    }
    return self;
}
```

- `fawakefromnib`
```objc
- (void)awakeFromNib {
    [super awakeFromNib];
    
    <#statements#>
}
```

- `fsetselected`
```objc
- (void)setSelected:(BOOL)selected animated:(BOOL)animated {
    [super setSelected:selected animated:animated];

    <#statements#>
}
```

### UIViewController
- `fvcvwa`
```objc
- (void)viewWillAppear:(BOOL)animated {
    [super viewWillAppear:animated];

    <#statements#>
}
```

- `fvcvda`
```objc
- (void)viewDidAppear:(BOOL)animated {
    [super viewDidAppear:animated];

    <#statements#>
}
```

- `fvcvwda`
```objc
- (void)viewWillDisappear:(BOOL)animated {
    [super viewWillDisappear:animated];

    <#statements#>
}
```

- `fvcvdda`
```objc
- (void)viewDidDisappear:(BOOL)animated {
    [super viewDidDisappear:animated];

    <#statements#>
}
```

- `fvcvwls`
```objc
- (void)viewWillLayoutSubviews {
    [super viewWillLayoutSubviews];

    <#statements#>
}
```

- `fvcvdls`
```objc
- (void)viewDidLayoutSubviews {
    [super viewDidLayoutSubviews];

    <#statements#>
}
```

### UIView
- `fvlayoutsubviews`
```objc
- (void)layoutSubviews {
    [super layoutSubviews];
    
    <#statements#>
}
```

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

- `ftvtemplate`
```objc
#pragma mark - UITableViewDataSource

- (NSInteger)numberOfSectionsInTableView:(UITableView *)tableView {
    return <#statements#>;
}

- (NSInteger)tableView:(UITableView *)tableView numberOfRowsInSection:(NSInteger)section {
    return <#statements#>;
}

- (UITableViewCell *)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath {
    <#UITableViewCell#> *cell = [tableView dequeueReusableCellWithIdentifier:<#Identifier#> forIndexPath:indexPath];
    
    return cell;
}

#pragma mark - UITableViewDelegate

- (CGFloat)tableView:(UITableView *)tableView heightForRowAtIndexPath:(NSIndexPath *)indexPath {
    return <#UITableViewAutomaticDimension#>;
}

- (nullable UIView *)tableView:(UITableView *)tableView viewForHeaderInSection:(NSInteger)section {
    return <#nil#>;
}

- (CGFloat)tableView:(UITableView *)tableView heightForHeaderInSection:(NSInteger)section {
    return <#CGFLOAT_MIN#>;
}

- (nullable UIView *)tableView:(UITableView *)tableView viewForFooterInSection:(NSInteger)section {
    return <#nil#>;
}

- (CGFloat)tableView:(UITableView *)tableView heightForFooterInSection:(NSInteger)section {
    return <#CGFLOAT_MIN#>;
}

- (void)tableView:(UITableView *)tableView didSelectRowAtIndexPath:(NSIndexPath *)indexPath {
    //[tableView deselectRowAtIndexPath:indexPath animated:YES];
    <#statements#>
}
```

- `ftvnos`
```objc
- (NSInteger)numberOfSectionsInTableView:(UITableView *)tableView {
    return <#statements#>;
}
```

- `ftvnor`
```objc
- (NSInteger)tableView:(UITableView *)tableView numberOfRowsInSection:(NSInteger)section {
    return <#statements#>;
}
```

- `ftvcfr`
```objc
- (UITableViewCell *)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath {
    <#UITableViewCell#> *cell = [tableView dequeueReusableCellWithIdentifier:<#Identifier#> forIndexPath:indexPath];
 
    return cell;
}
```

- `ftvhfr`
```objc
- (CGFloat)tableView:(UITableView *)tableView heightForRowAtIndexPath:(NSIndexPath *)indexPath {
    return <#UITableViewAutomaticDimension#>;
}
```

- `ftvvfh`
```objc
- (nullable UIView *)tableView:(UITableView *)tableView viewForHeaderInSection:(NSInteger)section {
    return <#nil#>;
}
```

- `ftvhfh`
```objc
- (CGFloat)tableView:(UITableView *)tableView heightForHeaderInSection:(NSInteger)section {
    return <#CGFLOAT_MIN#>;
}
```

- `ftvvff`
```objc
- (nullable UIView *)tableView:(UITableView *)tableView viewForFooterInSection:(NSInteger)section {
    return <#nil#>;
}
```

- `ftvhff`
```objc
- (CGFloat)tableView:(UITableView *)tableView heightForFooterInSection:(NSInteger)section {
    return <#CGFLOAT_MIN#>;
}
```

- `ftvdsr`
```objc
- (void)tableView:(UITableView *)tableView didSelectRowAtIndexPath:(NSIndexPath *)indexPath {
    //[tableView deselectRowAtIndexPath:indexPath animated:YES];
    
    <#statements#>
}
```

- `ctvregistercellnib`
```objc
    [<#self.tableView#> registerNib:[UINib nibWithNibName:<#nibName#> bundle:<#nil#>] forCellReuseIdentifier:<#Identifier#>];
```

- `ctvregistercellclass`
```objc
    [<#self.tableView#> registerClass:<#Class#> forCellReuseIdentifier:<#Identifier#>];
```

- `ctvregisterheaderfooternib`
```objc
    [<#self.tableView#> registerNib:[UINib nibWithNibName:<#nibName#> bundle:<#nil#>] forHeaderFooterViewReuseIdentifier:<#Identifier#>];
```

- `ctvregisterheaderfooterclass`
```objc
    [<#self.tableView#> registerClass:<#Class#> forHeaderFooterViewReuseIdentifier:<#Identifier#>];
```

### UITableViewItemsKit

- `ftviktemplate`
```objc
#pragma mark - UITableViewItemsDelegate

- (NSArray<UITableViewItem *> *)tableViewItemsInTableView:(UITableView *)tableView {
    return @[
             //
             ({
                 UITableViewItem *model = [[UITableViewItem alloc] init];
                 model.viewForHeader = ^UIView *(UITableView *tableView, NSInteger section) {
                     <#UITableViewHeaderFooterView#> *view = [tableView dequeueReusableHeaderFooterViewWithIdentifier:<#Identifier#>];

                     return view;
                 };
                 // model.headerColor = <#[UIColor whiteColor]#>;
                 model.heightForHeader = ^CGFloat(UITableView *tableView, NSInteger section) {
                     return <#height#>;
                 };
                 model.viewForFooter = ^UIView *(UITableView *tableView, NSInteger section) {
                     <#UITableViewHeaderFooterView#> *view = [tableView dequeueReusableHeaderFooterViewWithIdentifier:<#Identifier#>];

                     return view;
                 };
                 // model.footerColor = <#[UIColor whiteColor]#>;
                 model.heightForFooter = ^CGFloat(UITableView *tableView, NSInteger section) {
                     return <#height#>;
                 };
                 model.numberOfRows = 1;
                 model.cellForRow = ^UITableViewCell *(UITableView *tableView, NSIndexPath *indexPath) {
                     <#UITableViewCell#> *cell = [tableView dequeueReusableCellWithIdentifier:<#Identifier#> forIndexPath:indexPath];

                     return cell;
                 };
                 model.heightForRow = ^CGFloat(UITableView *tableView, NSIndexPath *indexPath) {
                     return <#UITableViewAutomaticDimension#>;
                 };
                 model.didSelectRow = ^(UITableView *tableView, NSIndexPath *indexPath) {
                     <#statements#>
                 };
                 model;
             }),
             ];
}
```

- `ctvikitem`
```objc
             //
             ({
                 UITableViewItem *model = [[UITableViewItem alloc] init];
                 model.viewForHeader = ^UIView *(UITableView *tableView, NSInteger section) {
                     <#UITableViewHeaderFooterView#> *view = [tableView dequeueReusableHeaderFooterViewWithIdentifier:<#Identifier#>];

                     return view;
                 };
                 // model.headerColor = <#[UIColor whiteColor]#>;
                 model.heightForHeader = ^CGFloat(UITableView *tableView, NSInteger section) {
                     return <#height#>;
                 };
                 model.viewForFooter = ^UIView *(UITableView *tableView, NSInteger section) {
                     <#UITableViewHeaderFooterView#> *view = [tableView dequeueReusableHeaderFooterViewWithIdentifier:<#Identifier#>];

                     return view;
                 };
                 // model.footerColor = <#[UIColor whiteColor]#>;
                 model.heightForFooter = ^CGFloat(UITableView *tableView, NSInteger section) {
                     return <#height#>;
                 };
                 model.numberOfRows = 1;
                 model.cellForRow = ^UITableViewCell *(UITableView *tableView, NSIndexPath *indexPath) {
                     <#UITableViewCell#> *cell = [tableView dequeueReusableCellWithIdentifier:<#Identifier#> forIndexPath:indexPath];

                     return cell;
                 };
                 model.heightForRow = ^CGFloat(UITableView *tableView, NSIndexPath *indexPath) {
                     return <#UITableViewAutomaticDimension#>;
                 };
                 model.didSelectRow = ^(UITableView *tableView, NSIndexPath *indexPath) {
                     <#statements#>
                 };
                 model;
             }),
```

### UICollectionView

- `fcvtemplate`
```objc
#pragma mark - UICollectionViewDataSource

- (NSInteger)numberOfSectionsInCollectionView:(UICollectionView *)collectionView {
    return <#statements#>;
}

- (NSInteger)collectionView:(UICollectionView *)collectionView numberOfItemsInSection:(NSInteger)section {
    return <#statements#>;
}

- (UICollectionViewCell *)collectionView:(UICollectionView *)collectionView cellForItemAtIndexPath:(NSIndexPath *)indexPath {
    <#UICollectionViewCell#> *cell = [collectionView dequeueReusableCellWithReuseIdentifier:<#Identifier#> forIndexPath:indexPath];
    
    return cell;
}

- (UICollectionReusableView *)collectionView:(UICollectionView *)collectionView viewForSupplementaryElementOfKind:(NSString *)kind atIndexPath:(NSIndexPath *)indexPath {
    UICollectionReusableView *reusableView = nil;
    if(kind == UICollectionElementKindSectionHeader) {
        reusableView = [collectionView reusableHeaderWithIdentifier:<#Identifier#> indexPath:indexPath];
    }
    else if (kind == UICollectionElementKindSectionFooter) {
        reusableView = [collectionView reusableFooterWithIdentifier:<#Identifier#> indexPath:indexPath];
    }

    return reusableView;
}

#pragma mark - UICollectionViewDelegateFlowLayout

- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout sizeForItemAtIndexPath:(NSIndexPath *)indexPath {
    return CGSizeMake(<#0#>, <#0#>);
}

- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout referenceSizeForHeaderInSection:(NSInteger)section {
    return CGSizeMake(<#0#>, <#0#>);
}

- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout*)collectionViewLayout referenceSizeForFooterInSection:(NSInteger)section {
    return CGSizeMake(<#0#>, <#0#>);
}

- (CGFloat)collectionView:(UICollectionView *)collectionView layout:(nonnull UICollectionViewLayout *)collectionViewLayout minimumInteritemSpacingForSectionAtIndex:(NSInteger)section {
    return <#0#>;
}

- (CGFloat)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout minimumLineSpacingForSectionAtIndex:(NSInteger)section {
    return <#0#>;
}

- (UIEdgeInsets)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout insetForSectionAtIndex:(NSInteger)section {
    return UIEdgeInsetsMake(<#0#>, <#0#>, <#0#>, <#0#>);
}

#pragma mark - UICollectionViewDelegate

- (void)collectionView:(UICollectionView *)collectionView didSelectItemAtIndexPath:(NSIndexPath *)indexPath {
    <#statements#>
}
```

- `fcvnos`
```objc
- (NSInteger)numberOfSectionsInCollectionView:(UICollectionView *)collectionView {
    return <#statements#>;
}
```

- `fcvnoi`
```objc
- (NSInteger)collectionView:(UICollectionView *)collectionView numberOfItemsInSection:(NSInteger)section {
    return <#statements#>;
}
```

- `fcvcfi`
```objc
- (UICollectionViewCell *)collectionView:(UICollectionView *)collectionView cellForItemAtIndexPath:(NSIndexPath *)indexPath {
    <#UICollectionViewCell#> *cell = [collectionView dequeueReusableCellWithReuseIdentifier:<#Identifier#> forIndexPath:indexPath];

    return cell;
}
```

- `fcvvfseok`
```objc
- (UICollectionReusableView *)collectionView:(UICollectionView *)collectionView viewForSupplementaryElementOfKind:(NSString *)kind atIndexPath:(NSIndexPath *)indexPath {
    UICollectionReusableView *reusableView = nil;
    if(kind == UICollectionElementKindSectionHeader) {
        reusableView = [collectionView reusableHeaderWithIdentifier:<#Identifier#> indexPath:indexPath];
    }
    else if (kind == UICollectionElementKindSectionFooter) {
        reusableView = [collectionView reusableFooterWithIdentifier:<#Identifier#> indexPath:indexPath];
    }
    
    return reusableView;
}
```

- `fcvsfi`
```objc
- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout sizeForItemAtIndexPath:(NSIndexPath *)indexPath {
    return CGSizeMake(<#0#>, <#0#>);
}
```

- `fcvrsfh`
```objc
- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout referenceSizeForHeaderInSection:(NSInteger)section {
    return CGSizeMake(<#0#>, <#0#>);
}
```

- `fcvrsff`
```objc
- (CGSize)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout*)collectionViewLayout referenceSizeForFooterInSection:(NSInteger)section {
    return CGSizeMake(<#0#>, <#0#>);
}
```

- `fcvmisfs`
```objc
- (CGFloat)collectionView:(UICollectionView *)collectionView layout:(nonnull UICollectionViewLayout *)collectionViewLayout minimumInteritemSpacingForSectionAtIndex:(NSInteger)section {
    return <#0#>;
}
```

- `fcvmlsfs`
```objc
- (CGFloat)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout minimumLineSpacingForSectionAtIndex:(NSInteger)section {
    return <#0#>;
}
```

- `fcvifs`
```objc
- (UIEdgeInsets)collectionView:(UICollectionView *)collectionView layout:(UICollectionViewLayout *)collectionViewLayout insetForSectionAtIndex:(NSInteger)section {
    return UIEdgeInsetsMake(<#0#>, <#0#>, <#0#>, <#0#>);
}
```

- `fcvdsi`
```objc
- (void)collectionView:(UICollectionView *)collectionView didSelectItemAtIndexPath:(NSIndexPath *)indexPath {
    <#statements#>
}
```

- `ccvregisterheadernib`
```objc
    [<#self.collectionView#> registerNib:[UINib nibWithNibName:<#nibName#> bundle:<#nil#>] forSupplementaryViewOfKind:UICollectionElementKindSectionHeader withReuseIdentifier:<#Identifier#>];
```

- `ccvregisterfooternib`
```objc
    [<#self.collectionView#> registerNib:[UINib nibWithNibName:<#nibName#> bundle:<#nil#>] forSupplementaryViewOfKind:UICollectionElementKindSectionFooter withReuseIdentifier:<#Identifier#>];
```

- `ccvregistercellnib`
```objc
    [<#self.collectionView#> registerNib:[UINib nibWithNibName:<#nibName#> bundle:<#nil#>] forCellWithReuseIdentifier:<#Identifier#>];
```

- `ccvregisterheaderclass`
```objc
    [<#self.collectionView#> registerClass:<#Class#> forSupplementaryViewOfKind:UICollectionElementKindSectionHeader withReuseIdentifier:<#Identifier#>];
```

- `ccvregisterfooterclass`
```objc
    [<#self.collectionView#> registerClass:<#Class#> forSupplementaryViewOfKind:UICollectionElementKindSectionFooter withReuseIdentifier:<#Identifier#>];
```

- `ccvregistercellclass`
```objc
    [<#self.collectionView#> registerClass:<#Class#> forCellWithReuseIdentifier:<#Identifier#>];
```

### NSNotification

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

