# Dart Package Template

Dart & Flutter Packages by DevCetra.com & contributors.

[![pub package](https://img.shields.io/pub/v/df_log.svg)](https://pub.dev/packages/df_log)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://raw.githubusercontent.com/robmllze/df_log/main/LICENSE)
[![Buy Me a Coffee](https://img.shields.io/badge/-buy_me_a%C2%A0coffee-gray?logo=buy-me-a-coffee)](https://www.buymeacoffee.com/robmllze)

## Summary

A package that provides logging utilities for better debugging. For a full feature set, please refer to the [API reference](https://pub.dev/documentation/df_log/).

## Usage Example

```dart
void main() {
  Here().debugLog('This is a log!'); // prints: "⚪️ [main] This is a log!"
  Here().debugLogError(
    'This is an error log!',
  ); // prints: "🔴 [main] This is an error log!"
  Here().debugLogAlert(
    'This is an alert log!',
  ); // prints: "🟠 [main] This is an alert log!"
  Here().debugLogIgnore(
    'This is an ignore log!',
  ); // prints: "🟡 [main] This is an ignore log!"
  Here().debugLogInfo(
    'This is an info log!',
  ); // prints: "🟣 [main] This is an info log!"
  Here().debugLogStart(
    'This is a start log!',
  ); // prints: "🔵 [main] This is a start log!"
  Here().debugLogStop(
    'This is a stop log!',
  ); // prints: "⚫ [main] This is a stop log!"
  Here().debugLogSuccess(
    'This is a success log!',
  ); // prints: "🟢 [main] This is a success log!"

  printRed(someFunction()); // prints: "someFunction" in red
  printGreen(anotherFunction()); // prints: "48"
  printLightPurple('You can also print in other color!');
}

String? someFunction() {
  return Here().scope;
}

int? anotherFunction() {
  return Here().lineNumber; // this is line 48
}
```

## Installation

Use this package as a dependency by adding it to your `pubspec.yaml` file (see [here](https://pub.dev/packages/df_log/install)).

---

## Contributing and Discussions

This is an open-source project, and we warmly welcome contributions from everyone, regardless of experience level. Whether you're a seasoned developer or just starting out, contributing to this project is a fantastic way to learn, share your knowledge, and make a meaningful impact on the community.

### Ways you can contribute:

- **Join the discussions and ask questions:** Your curiosity can lead to valuable insights and improvements.
- **Buy me a coffee:** If you'd like to support the project financially, consider [buying me a coffee](https://www.buymeacoffee.com/robmllze). Your support helps cover the costs of development and keeps the project growing.
- **Share your ideas:** Every perspective matters, and your ideas can spark innovation.
- **Report bugs:** Help us identify and fix issues to make the project more robust.
- **Suggest improvements or new features:** Your ideas can help shape the future of the project.
- **Help clarify documentation:** Good documentation is key to accessibility. You can make it easier for others to get started by improving or expanding our documentation.
- **Write articles:** Share your knowledge by writing tutorials, guides, or blog posts about your experiences with the project. It's a great way to contribute and help others learn.

No matter how you choose to contribute, your involvement is greatly appreciated and valued!

---

### Join Reddit Discussions:

💬 https://www.reddit.com/r/df_log/

### Join GitHub Discussions:

💬 https://github.com/robmllze/df_log/discussions/

### Chief Maintainer:

📧 Email _Robert Mollentze_ at robmllze@gmail.com

### Dontations:

If you're enjoying this package and find it valuable, consider showing your appreciation with a small donation. Every bit helps in supporting future development. You can donate here:

https://www.buymeacoffee.com/robmllze

---

## License

This project is released under the MIT License. See [LICENSE](https://raw.githubusercontent.com/robmllze/df_log/main/LICENSE) for more information.
