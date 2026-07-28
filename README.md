# 🚀 DevBuddy Showcase

A premium AI-augmented EdTech platform built with Flutter, delivering a structured learning experience with a strong focus on Clean Architecture and modern UI implementations



## ⚠️ Project Status & About

This repository serves as a **UI and Architecture Showcase** for a private startup project.
It is currently a **Work in Progress (WIP)**, highlighting the frontend design, the robust architectural foundation, and the strategic use of AI-assisted prototyping tools for rapid development. The repository does not contain the complete business logic or sensitive backend integrations.

## 🎥 Application Demo

**Demo:**


https://github.com/user-attachments/assets/79bac616-74b6-495f-b4ef-708fbc5d1b09


Watch the application demo showcasing the current progress, dual-mode experience, persona assessment flow, and premium UI animations.

## 🚀 Key Features

**🔒 Secure Authentication**

* Passwordless authentication
* Email and Phone OTP verification
* Multi-gate secure routing

**🧠 Developer Persona Assessment**

* Interactive scenario-based quiz
* Custom tech archetype generation
* Smart work-style environment fit

**🎮 Learning Hub & Gamification**

* Interactive roadmap progression
* XP points and streak tracking
* 3-tier learning zones

**🌍 Localization**

* Arabic (RTL)
* English (LTR)
* Powered by easy_localization

**🎨 Theme & UI**

* Premium True Dark Mode and Light Mode
* Glassmorphism effects
* Fully responsive layouts using flutter_screenutil

## 🛠️ Tech Stack & Architecture

* **Framework:** Flutter (Dart)
* **Architecture:** Feature-First Clean Architecture (Data, Domain, & Presentation Layers)
* **State Management:** BLoC / Cubit (flutter_bloc)
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

