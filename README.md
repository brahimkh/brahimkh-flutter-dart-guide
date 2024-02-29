# Flutter And Dart Guide 

- [Introduction](#introduction)

- [Dart Programming](#dart-programming) 
   - [Style](#dart-style)

- [Flutter Framework](#flutter-framework) 

## Introduction 

The Flutter and Dart Guide serves as a tool to expedite developers' work by facilitating collaboration, simplifying learning, enhancing code readability, and promoting standardization within our company. Additionally, we must prepare documents for the CUBETIQS government, All members have created by [Man Brahim](https://github.com/brahimkh), [ Chea Kit](https://github.com/cheakit) and [Son Phumrin](https://github.com/SonPhumrin1) are included.

## Dart Programming

### Style

Style is an essential aspect of good coding practice. It emphasizes consistent naming conventions, logical ordering, and proper formatting, which collectively contribute to the clarity and readability of code.


#### Identifiers
Identifiers come in three flavors in Dart.
- UpperCamelCase names capitalize the first letter of each word, including the first.

- lowerCamelCase names capitalize the first letter of each word, except the first which is always lowercase, even if it's an acronym.

- lowercase_with_underscores names use only lowercase letters, even for acronyms, and separate words with _.

Example 
  
- Using UpperCamelCase
<table>
<thead><tr><th>Bad</th><th>Good</th></tr></thead>
<tbody>
<tr><td>

```dart
class Menucontroller {...}

class httpRequest {...}

typedef predicate <T> = bool Function(T value);

```

</td><td>


```dart
class MenuController {...}

class HttpRequest {...}

typedef Predicate <T> = bool Function(T value);

```
</td></tr>

</tbody>

</table>

- Using lowerCamelCase
<table>
<thead><tr><th>Bad</th><th>Good</th></tr></thead>
<tbody>
<tr><td>

```dart
const PI = 3.14;
const DefaultTimeout = 1000;
final URL_SCHEME = RegExp('^([a-z]+):');

class Dice {
  static final NUMBER_GENERATOR = Random();
}

```

</td><td>


```dart
const pi = 3.14;
const defaultTimeout = 1000;
final urlScheme = RegExp('^([a-z]+):');

class Dice {
  static final numberGenerator = Random();
}

```
</td></tr>

</tbody>

</table>


- lowercase_with_underscores
<table>
<thead><tr><th>Bad</th><th>Good</th></tr></thead>
<tbody>
<tr><td>

```dart
mypackage
└─ lib
   └─ file-system.dart
   └─ SliderMenu.dart

```

</td><td>


```dart
my_package
└─ lib
   └─ file_system.dart
   └─ slider_menu.dart
```
</td></tr>

</tbody>

</table>
