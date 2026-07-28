<div align="center">

# 🚀 DevBuddy Showcase

**A premium AI augmented EdTech platform built with Flutter delivering a structured learning experience**

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](#)
[![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)](#)
[![Clean Architecture](https://img.shields.io/badge/Architecture-Clean-success?style=for-the-badge)](#)
[![State Management](https://img.shields.io/badge/State_Management-BLoC%2FCubit-blueviolet?style=for-the-badge)](#)

A showcase project demonstrating architectural proficiency with a strong focus on Clean Architecture modern UI implementations and scalable feature modules

https://github.com/user-attachments/assets/79bac616-74b6-495f-b4ef-708fbc5d1b09
</div>

---

## ✨ Key Features

### 🔐 Secure Authentication & Onboarding
* Passwordless OTP authentication flow
* Developer Persona Assessment engine
* Dynamic routing based on user profiles

### 🎨 Premium UI & Experience
* Premium True Dark Mode and Light Mode
* Glassmorphism effects and modern aesthetics
* Fully responsive layouts across all devices
* Engaging animations with lottie and audioplayers

### 🏗️ Advanced Architecture
* Feature First Clean Architecture (Data Domain & Presentation Layers)
* Robust Dependency Injection setup
* Offline caching strategies and mock first implementation

---

## 🛠️ Tech Stack & Architecture

* **Framework:** Flutter (Dart)
* **Architecture:** Feature First Clean Architecture
* **State Management:** BLoC / Cubit (flutter_bloc)
* **Dependency Injection:** get_it
* **Networking:** dio & flutter_secure_storage
* **Local Storage:** hive
* **Localization:** easy_localization
* **Animations:** lottie & audioplayers

---

## 📂 Architectural Overview

```text
project_root/
│
├── lib/
│   ├── core/
│   │   ├── error/
│   │   └── network/
│   │
│   ├── features/
│   │   ├── auth/
│   │   ├── onboarding/
│   │   └── pro_mode/
│   │
│   ├── shared/
│   │
│   └── main.dart
│
├── pubspec.yaml
└── README.md* **State Management:** BLoC / Cubit (flutter_bloc)
* **Dependency Injection:** get_it
* **Networking:** dio & flutter_secure_storage
* **Local Storage:** hive
* **Localization:** easy_localization
* **Animations:** lottie & audioplayers

## 🏗️ Architectural Overview

```text
project_root/
│
├── lib/
│   ├── core/
│   │   ├── theme/                 # Global themes and providers
│   │   ├── use_case/              # Base use cases
│   │   └── utils/                 # Helpers and constants
│   │
│   ├── features/
│   │   ├── auth/                  # Authentication Feature
│   │   │   ├── data/
│   │   │   │   ├── datasources/   # Remote & local data sources
│   │   │   │   ├── models/        # Data models (JSON parsing)
│   │   │   │   └── repositories/  # Repository implementations
│   │   │   ├── domain/
│   │   │   │   ├── entities/      # Pure domain entities
│   │   │   │   └── repositories/  # Abstract repository contracts
│   │   │   └── presentation/
│   │   │       ├── cubit/         # State management
│   │   │       └── screens/       # Auth UI and Wrappers
│   │   │
│   │   ├── onboarding/            # Onboarding & Routing Feature
│   │   │   └── screens/
│   │   │
│   │   └── pro_mode/              # Professional Dashboard Feature
│   │       ├── data/
│   │       ├── domain/
│   │       └── presentation/
│   │
│   ├── shared/                    # Reusable cross-feature widgets
│   │
│   ├── PROJECT_SPEC.md            # Master spec & architecture guide
│   └── main.dart                  # Entry point & DI initialization
│
├── pubspec.yaml
└── README.md

