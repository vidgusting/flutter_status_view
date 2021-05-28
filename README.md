# status_view

Display status just like WhatsApp & Instagram..

## Installation

You just need to add ```status_view``` as a dependency in your pubspec.yaml file.

```bash
dependencies:
  status_view: ^0.0.1
```

## Usage

```dart
StatusView(
            radius: 40,
            spacing: 15,
            strokeWidth: 2,
            indexOfSeenStatus: 2,
            numberOfStatus: 5,
            padding: 4,
            centerImageUrl: "https://picsum.photos/200/300",
            seenColor: Colors.grey,
            unSeenColor: Colors.red,
          ),
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.