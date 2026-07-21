# Meals

A Flutter recipe app that lets users browse meal categories, view meal details, mark favorites, and apply dietary filters.

## Features

- Category grid view for meal browsing
- Meal detail screen with ingredient and step information
- Favorites management for quick access to saved meals
- Dietary filters for gluten-free, lactose-free, vegetarian, and vegan meals
- Drawer navigation and tabs for categories and favorites
- Custom theming with Material 3 and Google Fonts

## Project Structure

- `lib/main.dart` – application entrypoint and theme setup
- `lib/screens/` – screen widgets for tabs, categories, meals, filters, and meal details
- `lib/widgets/` – reusable UI components such as category and meal cards
- `lib/models/` – data models for category and meal definitions
- `lib/data/dummy_data.dart` – sample meal/category data used by the app

## Getting Started

### Prerequisites

- Flutter SDK installed
- Compatible IDE such as Visual Studio Code or Android Studio

### Install dependencies

```bash
flutter pub get
```

### Run the app

```bash
flutter run
```

### Run tests

```bash
flutter test
```

## Dependencies

- `flutter`
- `cupertino_icons`
- `google_fonts`
- `transparent_image`

## Notes

- The app launches to `TabsScreen`, which handles tab navigation between categories and favorites.
- Filters are passed from `TabsScreen` to `FiltersScreen` and back using navigation results.
- The app uses local dummy data defined in `lib/data/dummy_data.dart`.

## License

This repository does not define a license. Add a `LICENSE` file if you want to specify terms.
