
# Customizable Ripple Animation

A Flutter package for creating customizable ripple animations, developed by Samandar Ahadjonov. This package allows easy integration of ripple effects into your Flutter applications with a high degree of customization.

## Features

- Customizable ripple color, size, and animation duration.
- Easy to integrate with any widget.
- High-performance animations using Flutter's native capabilities.

## Getting Started

To use the Customizable Ripple Animation package in your Flutter app, follow these steps:

### Installation

1. Add `customizable_ripple_animation` to your `pubspec.yaml` file:

```yaml
dependencies:
  customizable_ripple_animation: ^latest_version

```

### Usage

1. Import the package in your Dart code:

```Dart
import 'package:customizable_ripple_animation/customizable_ripple_animation.dart';
```

2. Define the ripple properties using the RippleData object:

```Dart
RippleData rippleData = RippleData(
    width: 100.0,
    height: 100.0,
    radius: 50.0,
    color: Colors.blue,
    opacity: 0.5,
    maxHeight: 150.0,
    maxWidth: 150.0,
    maxRadius: 75.0,
    rippleDuration: Duration(milliseconds: 600),
    animationDuration: Duration(milliseconds: 600),
);
```

3. Implement the CustomizableRippleAnimation widget:

```Dart
CustomizableRippleAnimation(
    child: YourWidget(), // Replace with your desired widget
    data: rippleData,
)
```

### Customization Options

- width: Initial width of the ripple.
- height: Initial height of the ripple.
- radius: Initial border radius of the ripple.
- color: Color of the ripple.
- opacity: Opacity of the ripple color.
- maxHeight: Maximum height during animation.
- maxWidth: Maximum width during animation.
- maxRadius: Maximum border radius during animation.
- rippleDuration: Duration of the ripple effect.
- animationDuration: Duration of the entire animation cycle.

Feel free to reach out for any questions or suggestions regarding this package. Happy coding!



## Authors

- [@ahadjonovss](https://github.com/ahadjonovss)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

[GitHub source](https://github.com/ahadjonovss/customizable_ripple_animation.git)


## FAQ

### 1. What is Customizable Ripple Animation?

Customizable Ripple Animation is a Flutter package developed by Samandar Ahadjonov that enables you to add interactive ripple animations to Flutter widgets. It allows developers to create engaging UI effects with ease.

### 2. How can I install the package in my Flutter project?

You can install the Customizable Ripple Animation package by adding the following line to your pubspec.yaml file under the dependencies section:

``` yaml
dependencies:
  customizable_ripple_animation: ^latest_version
  ```

### 3. How do I use the Customizable Ripple Animation package?

To use the package, follow these steps:

- Import the package in your Dart code:

``` Dart
import 'package:customizable_ripple_animation/customizable_ripple_animation.dart';
```

- Define the ripple properties using the RippleData object, customizing parameters like width, height, color, and more.

- Implement the CustomizableRippleAnimation widget, providing your desired child widget and the RippleData object as its data.


### 4. Can I customize the appearance of the ripple effect?

Yes, you have extensive customization options for the ripple effect, including properties such as size, color, radius, opacity, and animation duration. You can tailor the ripple effect to match your app's design and user experience.

### 5. How do I control the duration of the ripple animation?

You can control the duration of the ripple animation by setting the rippleDuration and animationDuration properties in the RippleData object. Adjusting these 

### 6. Is there an example application available to see the package in action?

Yes, you can find a detailed example application in the example directory of the package. This example demonstrates various features and customizations of the Customizable Ripple Animation package.

### 7. Can I contribute to the development of this package?

Absolutely! Contributions are welcome. If you have ideas for improvements, new features, or bug fixes, feel free to submit pull requests or open issues on the package's [GitHub repository](https://github.com/ahadjonovss/customizable_ripple_animation.git).

### 8. How can I contact the author for questions or support?

You can reach out to the author, Samandar Ahadjonov, on their Linktree profile: [LinkTree](https://linktr.ee/ahadjonovss?fbclid=PAAaYJKH3gEwbffi3QyH_kFINfEBhZZEAERqz-NPizYR3qnZnwjEzEVuWthxw_aem_AVcdkYfpLEGeFKvfNPpq9JCZ3wfUe-yKutCVXwHbPM3zm486macDAME7oGkF8Qm76Jc). Feel free to contact them for any package-related questions or support.

Feel free to expand or modify this FAQ section to address specific questions or concerns your users might have about your Customizable Ripple Animation package.
## License

[UMD GROUP](https://t.me/umdgroupuz)

