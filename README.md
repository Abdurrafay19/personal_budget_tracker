<div align="center">
  <h1>Personal Budget Tracker</h1>

  <p><strong>A cross-platform financial dashboard and AI-driven budget manager built in 24 hours.</strong></p>

  <p>
    <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" />
    <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white" />
    <img alt="Hive" src="https://img.shields.io/badge/Hive_DB-FFCA28?style=flat&logo=databricks&logoColor=black" />
    <img alt="SOFTEC 2026" src="https://img.shields.io/badge/SOFTEC_2026-App_Dev_Hackathon-blueviolet" />
  </p>
</div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Architecture & Folders](#-architecture--folders)
- [The Team](#-the-team)
- [License](#-license)

---

## 🚀 About the Project

This application was developed as a competitive entry for the **SOFTEC 2026 App Development Competition**. Built entirely during an intense 24-hour coding sprint, our team set out to create a highly responsive, local-first personal finance application that helps users track liquidity, manage ledgers, and receive smart, AI-driven financial insights.

Because we were competing against the clock, we chose Flutter for its rapid UI rendering capabilities and Hive for instantaneous, NoSQL local data persistence, allowing us to deliver a complete, offline-capable application without relying on a slow external database.

### 🎯 Key Features
* **AI-Powered Financial Insights:** Integrates an AI consultation layer (`ai_services.dart`) to analyze the user's ledger and provide smart recommendations on cash flow trends.
* **Comprehensive Ledger System:** A highly optimized transaction logger featuring search, filter chips, and grouped transaction headers.
* **Goal Tracking Engine:** Allows users to set, edit, and visualize progress toward personal financial milestones using dynamic UI components (like wavy progress bars).
* **Local-First Architecture:** Utterly private and lightning-fast. All transaction and profile data is stored locally on the device using Hive NoSQL.
* **Cross-Platform:** Compiles seamlessly to Android, iOS, Windows, macOS, Linux, and Web from a single Dart codebase.

---

## 🛠 Tech Stack

* **Framework:** Flutter
* **Language:** Dart
* **Local Storage:** Hive (Fast, secure, NoSQL database for Flutter)
* **State Management:** Provider / Core Theme Providers
* **AI Integration:** Custom API hooks for AI financial analysis

---

## ⚙️ Getting Started

Follow these steps to run the application locally.

### Prerequisites
* [Flutter SDK](https://docs.flutter.dev/get-started/install) (latest stable channel)
* Android Studio / Xcode (for mobile emulation) or a connected device.

### Installation

**1. Clone the repository:**
```bash
git clone https://github.com/abdurrafay19/personal_budget_tracker.git
cd personal_budget_tracker

```

**2. Fetch Flutter dependencies:**

```bash
flutter pub get

```

**3. Run the application:**
Ensure you have a device connected or an emulator running, then execute:

```bash
flutter run

```

---

## 🏗 Architecture & Folders

Despite the 24-hour time constraint, the codebase was structured cleanly into distinct feature modules to prevent merge conflicts among team members:

```text
lib/
├── auth/          # Login, Signup, and Authentication flows
├── core/          # App themes, Hive DB service, global providers
├── goals/         # Financial milestone models and UI screens
├── home/          # Dashboard, liquidity metrics, and AI Insights
├── ledger/        # Transaction models, history screen, and search logic
├── navigation/    # Bottom navigation and global routing
├── profile/       # User settings and theme selection
└── shared/        # Reusable UI components (buttons, text fields)

```

---

## 🤝 The Team

This application was brought to life by a dedicated team of three during the SOFTEC 2026 competition. Building a polished, cross-platform app in 24 hours requires intense collaboration, and this project wouldn't exist without them.

* **Abdur Rafay** - [Role, e.g., Core Logic & AI Integration] - [@Abdurrafay19](https://github.com/Abdurrafay19)
* **Faizan Ahmed** - [Role, e.g., UI/UX & Frontend Development] - [@Blocky-l253098](https://github.com/Blocky-l253098)
* **Abdullah Hassan Butt** - [Role, e.g., Database & Ledger Architecture] - [@thatstheabdullah](https://github.com/thatstheabdullah)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
