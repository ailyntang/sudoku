# sudoku
iOS sudoku hinter


# To do
Next thing I need to do is to update to Xcode 11.4 and then run `carthage update` again.

At the moment RxSwift requires Swift 5.2 and I'm only running 5.1.3 locally. I assume if I update to Xcode 11.4, then I will be on Swift 5.1.3 (but have to check that).

````
192-168-1-119:sudoku ailyntang$ carthage update
*** Cloning RxSwift
*** Checking out RxSwift at "5.1.1"
*** xcodebuild output can be found in /var/folders/9g/nf4dcs393g31x4wfyvhlwld80000gn/T/carthage-xcodebuild.x7mDzQ.log
*** Downloading RxSwift.framework binary at "Catalyst.1"
***  Skipped installing RxSwift.framework binary due to the error:
	"Incompatible Swift version - framework was built with 5.2 (swiftlang-1103.0.32.1 clang-1103.0.32.29) and the local version is 5.1.3 (swiftlang-1100.0.282.1 clang-1100.0.33.15)."

    Falling back to building from the source
*** Building scheme "RxBlocking" in Rx.xcworkspace
*** Building scheme "RxTest" in Rx.xcworkspace
*** Building scheme "RxSwift" in Rx.xcworkspace
*** Building scheme "RxRelay" in Rx.xcworkspace
*** Building scheme "RxCocoa" in Rx.xcworkspace
```
