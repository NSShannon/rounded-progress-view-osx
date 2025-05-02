RoundedProgressView
===================

A simple rounded progress view for OS X.

![](demo.gif)

![](https://github.com/NSShannon/rounded-progress-view-osx/blob/master/%20progressview.png)

Customizable properties:

```objc

/// The line width of the receiver progress bar, defaults to 12.0f.
@property (nonatomic, assign) CGFloat progressLineWidth;

/// The progress line color, defaults to orange.
@property (nonatomic, strong) NSColor* progressLineColor;

/// The line width of the receiver background bar, defaults to 14.0f.
@property (nonatomic, assign) CGFloat backgroundLineWidth;

/// The background line color, defaults to white.
@property (nonatomic, strong) NSColor* backgroundLineColor;

/// The progress text color, defaults to textColor.
@property (nonatomic, strong) NSColor* progressTextColor;

/// Specifies the basic duration of the animation, in seconds, defaults to 0.4.
@property (nonatomic, assign) CFTimeInterval duration;

```
