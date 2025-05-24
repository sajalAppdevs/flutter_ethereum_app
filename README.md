# Flutter Ethereum NFT Marketplace App

A modern and beautiful Flutter application for NFT (Non-Fungible Token) marketplace on Ethereum blockchain. This app provides a sleek user interface for browsing and interacting with NFTs.

## Features

- 🎨 Modern and clean UI design
- 🔍 NFT search functionality
- 🖼️ NFT card display with stacked animation
- 👤 User profile management
- 🏠 Intuitive home screen with featured NFTs
- 🎯 Place bid functionality
- 📱 Responsive design for various screen sizes

## Screenshots

![Welcome Screen](assets/screenshot/one.jpg)
![Home Screen](assets/screenshot/two.jpg)

## Technologies Used

- Flutter SDK (>=2.17.6 <3.0.0)
- GetX for state management and navigation
- Custom widgets for reusable UI components
- Material Design components

## Dependencies

- `get: ^4.6.5` - State management and navigation
- `badges: ^2.0.3` - Badge widgets
- `font_awesome_flutter: ^10.1.0` - Icon pack
- `cupertino_icons: ^1.0.2` - iOS style icons

## Getting Started

### Prerequisites

- Flutter SDK
- Android Studio / VS Code
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/flutter_ethereum_app.git
```

2. Navigate to project directory
```bash
cd flutter_ethereum_app
```

3. Install dependencies
```bash
flutter pub get
```

4. Run the app
```bash
flutter run
```

## Project Structure

```
lib/
├── core/
│   └── constant/       # App constants (colors, images, etc.)
├── screens/
│   ├── home_screen.dart      # Main NFT browsing screen
│   ├── placebid_screen.dart  # NFT bidding screen
│   └── welcome_screen.dart   # App welcome screen
└── widgets/
    ├── custom_appbar_widget.dart   # Custom app bar
    ├── custom_dot_widget.dart      # Custom dot indicator
    ├── custom_input_widget.dart    # Custom input fields
    ├── customcard_widget.dart      # NFT card widget
    └── customsubcard_widget.dart   # Sub-card widget
```

## Custom Fonts

The app uses the OpenSans font family:
- OpenSans Regular
- OpenSans Bold

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
