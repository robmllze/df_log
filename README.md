# Dart Package Template

Dart & Flutter Packages by DevCetra.com & contributors.

[![pub package](https://img.shields.io/pub/v/df_log.svg)](https://pub.dev/packages/df_log)

## Summary

A package that provides logging utilities for better debugging. For a full feature set, please refer to the [API reference](https://pub.dev/documentation/df_log/).

## Usage Example

```dart
void main() {
  Here().debugLog('This is a log!'); // prints: "⚪️ [main] This is a log!"
  Here().debugLogError('This is an error log!'); // prints: "🔴 [main] This is an error log!"
  Here().debugLogAlert('This is an alert log!'); // prints: "🟠 [main] This is an alert log!"
  Here().debugLogIgnore('This is an ignore log!'); // prints: "🟡 [main] This is an ignore log!"
  Here().debugLogInfo('This is an info log!'); // prints: "🟣 [main] This is an info log!"
  Here().debugLogStart('This is a start log!'); // prints: "🔵 [main] This is a start log!"
  Here().debugLogStop('This is a stop log!'); // prints: "⚫ [main] This is a stop log!"
  Here().debugLogSuccess('This is a success log!'); // prints: "🟢 [main] This is a success log!"

  printRed(someFunction()); // prints: "someFunction" in red
  printGreen(anotherFunction()); // prints: "34"
  printLightPurple('You can also print in other colord!');
}

String? someFunction() {
  return Here().scope;
}

int? anotherFunction() {
  return Here().lineNumber; // line 34
```

## Installation

Use this package as a dependency by adding it to your `pubspec.yaml` file (see [here](https://pub.dev/packages/df_log/install)).

## Contributing and Discussions

This is an open-source project, and contributions are welcome from everyone, regardless of experience level. Contributing to projects is a great way to learn, share knowledge, and showcase your skills to the community. Join the discussions to ask questions, report bugs, suggest features, share ideas, or find out how you can contribute.

### Join GitHub Discussions:

💬 https://github.com/robmllze/df_log/discussions/

### Join Reddit Discussions:

💬 https://www.reddit.com/r/df_log/

### Chief Maintainer:

📧 Email _Robert Mollentze_ at robmllze@gmail.com

## License

This project is released under the MIT License. See [LICENSE](https://raw.githubusercontent.com/robmllze/df_log/main/LICENSE) for more information.
