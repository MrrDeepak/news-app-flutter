# NewsApp MVVM

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Intro
Welcome to the News App! This application provides a clean and intuitive interface to view the latest news articles. It is built using the MVVM (Model-View-ViewModel) architecture and consumes data from a news API.

News App developed with Flutter and API from [News API](https://newsapi.org)

## Technology
1. http<br />
This package contains a set of high-level functions and classes that make it easy to consume HTTP resources. It's multi-platform, and supports mobile, desktop, and the browser.
2. MVVM Architecture<br />
Model-View-ViewModel (MVVM) is a software design pattern that is structured to separate program logic and user interface controls.
3. Url Launcher<br />
Flutter plugin for launching a URL in the mobile platform. Supports iOS and Android.
4. JSON Serializable<br />
Automatically generate code for converting to and from JSON by annotating Dart classes.
5. card_swiper<br />
Swiper/Carousel for flutter, with multiple layouts, infinite loop. Compatible with Android & iOS.

#Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/news-app-flutter.git
```
2. Navigate to the Flutter project directory:
```
cd news-app-flutter
```
3. Install dependencies:
```
flutter pub get
```
4. Add API key:

 * Please open file   `lib/repository/news_api.dart`   and change `YOUR API KEY` in the variable `keyApi` with your own.

5. Run the application:
```
flutter run
```
This will launch the app on your connected device or emulator.

# License
This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

# Screenshots
![Flutter News App](https://github.com/amer787/flutter-news-app-mvvm/blob/main/screenshots/newsApp.png)
