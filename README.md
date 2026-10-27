## SeKO Rental – Vehicle Rental Application
SeKO (Sewa Kendaraan Online) is a mobile application built with Flutter and Dart designed to streamline the vehicle rental process. Whether users need a car for a family trip or a motorbike for a quick commute, SeKO provides a seamless interface to browse, book, and manage rentals.


## 🚀 Features
For Users:
- Vehicle Catalog: Browse a wide variety of vehicles (Cars, Motorbikes, etc.) with detailed specifications.

- Search & Filter: Find vehicles based on type, price range, brand, or availability.

- Booking System: Easy-to-use scheduling for pick-up and return dates.

- Real-time Availability: Check if a vehicle is ready for rent instantly.

- Order History: Track current rentals and view past transaction details.

- User Profile: Manage personal information and rental preferences.

- For Administrators (Optional/Planned):

- Inventory Management: Add, update, or remove vehicles from the fleet.

- Booking Oversight: Monitor active rentals and manage returns.


## 🛠 Tech Stack
Frontend: Flutter (UI Framework)

Language: Dart

State Management: [e.g., Provider / Riverpod / Bloc]

Backend: [e.g., Firebase / Supabase / REST API]

Database: [e.g., Cloud Firestore / PostgreSQL]

Local Storage: [e.g., Shared Preferences / Hive]



## 📸 Screenshots (TBA)
Home Screen	Vehicle Details	Booking Page
Home	Details	Booking


## 🏁 Getting Started
Prerequisites
Flutter SDK: ^3.x.x
Dart SDK: ^3.x.x
An IDE (Android Studio, VS Code, or IntelliJ)

Installation
1. **Clone the repository**

   ```bash
   git clone https://github.com/IvanVincentKwenandar/SeKO-Car-Rental-Apps.git
   cd SeKO-Car-Rental-Apps

2. **Install dependencies**

   ```bash
   flutter pub get

3. **Set up the environment**

   ```bash
   cp .env.seko .env

4. **Run the application**

   ```bash
   flutter run

## 📂 Project Structure

  lib/
  ├── core/           # Constants, themes, and shared utilities
  ├── data/           # Models, repositories, and data providers
  ├── providers/      # State management logic
  ├── ui/
  │   ├── screens/    # Main application screens (Home, Login, etc.)
  │   ├── widgets/    # Reusable UI components
  │   └── shared/     # Shared UI elements (buttons, inputs)
  └── main.dart       # Entry point of the application


## 🤝 Contributing
Contributions are welcome! If you'd like to improve SeKO, please follow these steps:

1. Fork the Project.

2. Create your Feature Branch (git checkout -b feature/AmazingFeature).

3. Commit your Changes (git commit -m 'Add some AmazingFeature').

4. Push to the Branch (git push origin feature/AmazingFeature).

5. Open a Pull Request.
