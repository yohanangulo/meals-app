# Meals App

Flutter application for exploring recipes and managing favorite meals. Built with modern Flutter architecture patterns including Riverpod for state management and Material Design 3.

## Features

- **Recipe Categories**: Browse meals organized by categories
- **Meal Details**: Detailed recipe information including ingredients and cooking instructions
- **Favorites System**: Save and manage favorite meals with persistent storage
- **Filtering**: Filter recipes by dietary preferences (gluten-free, vegetarian, vegan, lactose-free)
- **Navigation**: Smooth tab-based navigation with drawer menu

## Technical Stack

- **Framework**: Flutter 3.5.1+
- **State Management**: Riverpod 2.5.1
- **Theming**: Material Design 3 with Google Fonts (Lato)
- **Architecture**: Provider pattern with clear separation of concerns

## Project Structure

```
lib/
├── data/           # Static data and dummy content
├── models/         # Data models (Category, Meal)
├── providers/      # Riverpod providers for state management
├── screens/        # Application screens
├── widgets/        # Reusable UI components
└── main.dart       # Application entry point
```

## Architecture Overview

```
┌─────────────────┐
│   Presentation  │  Screens & Widgets
│     Layer       │  (UI Components)
└─────────────────┘
         │
┌─────────────────┐
│    Provider     │  Riverpod Providers
│     Layer       │  (State Management)
└─────────────────┘
         │
┌─────────────────┐
│     Data        │  Models & Static Data
│     Layer       │  (Meal, Category)
└─────────────────┘
```

## Key Architecture Decisions

- **Riverpod**: Chosen for robust state management with compile-time safety
- **Provider Pattern**: Clean separation between UI and business logic
- **Material Design 3**: Modern UI following Google's latest design guidelines

## Getting Started

### Prerequisites

- Flutter SDK 3.5.1 or higher
- Dart SDK compatible with Flutter version

### Installation

1. Clone the repository

```bash
git clone https://github.com/yohanangulo/meals-app.git
cd meals-app
```

2. Install dependencies

```bash
flutter pub get
```

3. Run the application

```bash
flutter run
```

## Dependencies

- `flutter_riverpod`: State management solution
- `google_fonts`: Custom typography with Lato font
- `transparent_image`: Image loading optimization
- `cupertino_icons`: iOS-style icons

## Screenshots

<div align="center">

| Meal details screen                                                                                                    | Meal filters                                                                                                           | Adding to favorites                                                                                                    |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| <img width="250" height="556" src="https://github.com/user-attachments/assets/072383cf-3f6c-41a4-9121-2d54687e0e3e" /> | <img width="250" height="556" src="https://github.com/user-attachments/assets/970c6bcb-6798-4298-8537-9e2ee1b63745" /> | <img width="250" height="556" src="https://github.com/user-attachments/assets/a414314d-121b-4e90-9a6e-f3ba242f1b76" /> |

</div>

## Development Practices

- **Clean Code**: Following Dart and Flutter best practices
- **State Management**: Centralized state with Riverpod providers
- **Component Architecture**: Reusable and testable widget components
- **Performance**: Optimized image loading and efficient state updates

---

**Built with Flutter | Developed by Yohan Angulo**
