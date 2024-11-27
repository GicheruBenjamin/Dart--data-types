Here’s the full `README.md` file rewritten for your Dart project:

---

# Dart Types Example

This project demonstrates various Dart data types and their usage. Each file in the `types` folder showcases a specific data type, including `bool`, `const`, `dynamic`, `final`, `list`, `map`, `number`, `rune`, `set`, and `string`. The `main.dart` file serves as the entry point, calling examples from each type-related file.

## Project Structure

The project is organized as follows:

```
dart-types/
├── main.dart       # Main entry point for the application
├── types/          # Folder for different type-specific files
│   ├── bool.dart   # Boolean type operations and examples
│   ├── const.dart  # Usage of `const` keyword and compile-time constants
│   ├── dynamic.dart # Working with dynamic types
│   ├── final.dart  # Usage of `final` keyword and immutable variables
│   ├── list.dart   # Working with lists
│   ├── map.dart    # Working with maps
│   ├── number.dart # Examples of `int`, `double`, and `num`
│   ├── rune.dart   # Working with Unicode runes and special characters
│   ├── set.dart    # Working with sets
│   └── strings.dart # String operations and examples
```

## How to Run

### 1. Install Dart

If you don't have Dart installed, follow the instructions on the [official Dart website](https://dart.dev/get-dart) to install it.

### 2. Clone the Repository

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/dart-types.git
cd dart-types
```

### 3. Run the Program

To execute the Dart program, use the following command:

```bash
dart run
```

This will run the `main.dart` file, which will print examples of each data type.

## Data Type Examples

### `bool`
The `bool` type represents a boolean value, either `true` or `false`.

Example (`bool.dart`):
```dart
bool isActive = true;
bool isCompleted = false;

print("Is Active: $isActive");
print("Is Completed: $isCompleted");
```

### `const`
The `const` keyword is used to define compile-time constants. Once defined, the value cannot be changed.

Example (`const.dart`):
```dart
const double pi = 3.14159;

print("Value of Pi: $pi");
```

### `dynamic`
The `dynamic` type allows variables to hold values of any type. Type checks are done at runtime, making it less type-safe than other types.

Example (`dynamic.dart`):
```dart
dynamic value = 42;
print("Dynamic value: $value");

value = "Now I'm a string!";
print("Dynamic value: $value");
```

### `final`
The `final` keyword defines variables that can only be set once. The value can be assigned only once, but unlike `const`, it doesn't have to be a compile-time constant.

Example (`final.dart`):
```dart
final String username = "Alice";

print("Username: $username");
```

### `list`
The `List` type represents an ordered collection of items. Lists can store multiple values of the same type.

Example (`list.dart`):
```dart
List<int> numbers = [1, 2, 3, 4, 5];
print("Numbers list: $numbers");

List<String> fruits = ["Apple", "Banana", "Cherry"];
print("Fruits list: $fruits");
```

### `map`
The `Map` type represents a collection of key-value pairs. Each key in a `Map` must be unique.

Example (`map.dart`):
```dart
Map<String, int> ages = {"Alice": 25, "Bob": 30};
print("Ages map: $ages");

Map<String, String> capitals = {
  "USA": "Washington, D.C.",
  "India": "New Delhi",
};
print("Capitals map: $capitals");
```

### `number`
Dart has three types for representing numbers: `int` (for whole numbers), `double` (for decimal numbers), and `num` (which can hold both).

Example (`number.dart`):
```dart
int wholeNumber = 42;
double decimalNumber = 3.14;
num flexibleNumber = 5; // Can be int or double

print("Integer: $wholeNumber");
print("Decimal: $decimalNumber");
print("Flexible: $flexibleNumber");
```

### `rune`
The `Rune` type is used to represent Unicode code points. This is useful for working with special characters like emojis.

Example (`rune.dart`):
```dart
Runes heart = Runes('\u2665');
print("Unicode Heart: ${String.fromCharCodes(heart)}");

Runes smile = Runes('\u1F60D');
print("Unicode Smile: ${String.fromCharCodes(smile)}");
```

### `set`
A `Set` is an unordered collection of unique items. Sets do not allow duplicate values.

Example (`set.dart`):
```dart
Set<int> uniqueNumbers = {1, 2, 3, 4, 5};
print("Set of unique numbers: $uniqueNumbers");

Set<String> uniqueFruits = {"Apple", "Banana", "Apple"};
print("Unique fruits set: $uniqueFruits"); // Duplicates removed
```

### `strings`
The `String` type represents a sequence of characters. Dart strings are immutable and support string interpolation.

Example (`strings.dart`):
```dart
String greeting = "Hello, Dart!";
String multilineString = '''This is a
multi-line string''';

print("Greeting: $greeting");
print("Multiline String: $multilineString");

String name = "Alice";
String introduction = "Hello, $name!";
print(introduction);
```

## Contributing

Feel free to fork this repository and contribute by adding new examples, fixing issues, or improving the documentation. If you have any questions or suggestions, feel free to open an issue or submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
```

---

### Explanation:

- **Overview**: Provides an introduction to the purpose of the project, with details on its structure and usage.
- **How to Run**: Step-by-step instructions for setting up and running the project.
- **Data Type Examples**: Describes the usage of each data type with corresponding code examples.
- **Contributing**: Encourages others to contribute to the project by adding new examples or improving the code.
- **License**: Specifies the project's open-source license (MIT License in this case).
