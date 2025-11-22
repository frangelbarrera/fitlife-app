# FitLife App - Flutter UI Template

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A clean and modern Flutter UI template designed for fitness and health tracking applications. This project demonstrates best practices in Flutter development, including custom components, state management, and responsive design. Perfect as a starting point for building mobile apps focused on wellness, exercise programs, diet tracking, and progress visualization.

## Features

- **Tabbed Navigation**: Intuitive bottom navigation with tabs for Programs, Diet, Results, and more.
- **Custom Components**: Reusable widgets like progress bars, charts, and card layouts for a consistent UI.
- **Responsive Design**: Adapts to different screen orientations and sizes.
- **Data Visualization**: Integrated charts and indicators for tracking fitness metrics.
- **Modular Architecture**: Easy to extend with new features or customize for specific needs.

## Technologies Used

- **Flutter**: Cross-platform framework for building native mobile apps.
- **Dart**: Programming language for Flutter development.
- **Packages**:
  - `flutter_rounded_progress_bar`: For custom progress indicators.
  - `bezier_chart`: For data visualization charts.
  - `percent_indicator`: For percentage-based UI elements.

## Installation

To run this project locally, ensure you have [Flutter](https://flutter.dev/docs/get-started/install) and [Dart](https://dart.dev/get-dart) installed on your system.

1. Clone the repository:
   ```bash
   git clone https://github.com/frangelbarrera/fitlife-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fitlife-app
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Usage

This template provides a foundation for fitness apps. Key screens include:
- **Programs**: Browse and select workout programs.
- **Diet**: Track meals and nutrition.
- **Results**: View progress charts and statistics.
- **Activity Details**: Detailed views for exercises and timers.

Customize the UI components in `lib/components/` and data models in `lib/models/` to fit your app's requirements.

## Project Structure

```
lib/
├── components/          # Reusable UI components
├── data/                # Static data (e.g., dishes)
├── models/              # Data models (e.g., Exercise)
├── pages/               # Screen pages
├── tabs/                # Tab-based navigation
└── main.dart            # App entry point
```

## Contributing

Contributions are welcome! If you'd like to improve this template:
1. Fork the repository.
2. Create a feature branch.
3. Make your changes and test thoroughly.
4. Submit a pull request.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


