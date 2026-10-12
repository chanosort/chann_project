# Chann Project

A Flutter web application for [briefly describe what your app does, e.g., "channel management and user authentication"].

## 👥 Group Members and Roles

| Name | Role | Responsibilities |
| :--- | :--- | :--- |
| [Cristian Troso] | Lead Developer | Project setup, routing, UI implementation, Git management |
| [Melissa Reas] | UI/UX Designer | Screen design, widget styling, user flow |
| [Jason James Ocno] | Backend/Logic | API integration (http), state management |

*(Adjust the table based on how many members are in your group. If you are working alone, just list yourself.)*

## 🛠️ Technology Stack

- **Framework:** [Flutter](https://flutter.dev/) (Stable Channel 3.47.2)
- **Language:** [Dart](https://dart.dev/) (3.13.2)
- **Routing:** [go_router](https://pub.dev/packages/go_router) (v18.0.2)
- **Networking:** [http](https://pub.dev/packages/http) (v1.6.0)
- **Target Platform:** Web (Chrome / Edge)

## 🚀 How to Run the Flutter Web Project

Follow these steps to run the project locally.

### Prerequisites
Make sure you have Flutter installed and configured for web development. Run `flutter doctor` to verify.

### Sample Run Section

```cmd
# 1. Get the project dependencies
flutter pub get

# 2. Run the project on Chrome
flutter run -d chrome

# 3. Build for web (for production)
flutter build web