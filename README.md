# iOS_CodeSnippets
# 使用方式
Xcode 的 Code Snippets 文件存放于 `~/Library/Developer/Xcode/UserData/CodeSnippets` 目录，只要直接把 `*.codesnippets` 文件放到这个目录下（若没有则自己创建），重启 Xcode 即可生效。

```
~/Library/Developer/Xcode/UserData/CodeSnippets
```

# 快捷键汇总
## Objective-C
### NSObject
* `pa` - 定义一个 `assign` 的 property
* `par` - 定义一个 `assign, readonly` 的 property
* `pc` - 定义一个 `copy` 的 property
* `ps` - 定义一个 `strong` 的property
* `psr` - 定义一个 `strong, readonly` 的property
* `pw` - 定义一个 `weak` 的property
* `pwr` - 定义一个 `weak, readonly` 的property

### Block
* `blockArguments` - 声明一个用于方法参数的 block
* `blockproperty` - 声明一个用于 property 的 block
* `blocktypedef` - 用 `typedef` 定义一个 block

### Method & Function
* `fnv` - 定义一个返回值为 `void` 的方法
* `fnv:` - 定义一个返回值为 `void` 且带参数的方法

### UIViewController
* `viewDidLayoutSubviews` - 展开 `viewDidLayoutSubviews:` 方法

### Other
* `weakSelf` - 定义一个 `weak` 的 `self` 指针
* `strongSelf` - 将 `weakSelf` 指针改为 `strong` 的 `self` 指针
* `Mark` - 展开一个 mark
* `static reference` - 定义一个 `static` 的指针
* `static` - 定义一个`static` 的值变量

## Swift
* `gls` - 展开`guard let self = self else { return }`
* `didSet` - 展开`didSet { }`
* `didSetModel` - 给 `view` 绑定 `model`
* `extension` - 展开`extension { }`
* `viewDidLayoutSubviews` - 展开`viewDidLayoutSubviews:` 方法
* `Mark` - 展开一个 mark

## RxSwift
* `RxBinder` - 展开 `Reactive extension`
* `RxBehaviorRelay` - 定义一个 `BehaviorRelay`
* `RxDriver` - 定义一个 `Driver`
