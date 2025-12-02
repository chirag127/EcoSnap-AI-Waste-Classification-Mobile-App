# EcoSnap-AI-Waste-Classification-Mobile-App

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App/ci.yml?style=flat-square&logo=githubactions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App?style=flat-square&logo=codecov)
![Tech Stack: React Native](https://img.shields.io/badge/Tech%20Stack-React%20Native-informational?style=flat-square&logo=react)
![Tech Stack: Expo](https://img.shields.io/badge/Tech%20Stack-Expo-000000?style=flat-square&logo=expo)
![Tech Stack: TypeScript](https://img.shields.io/badge/Tech%20Stack-TypeScript-3178C6?style=flat-square&logo=typescript)
![Lint/Format: Biome](https://img.shields.io/badge/Lint%2FFormat-Biome-informational?style=flat-square&logo=biome)
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App?style=flat-square&logo=github)

[![Star ⭐ this Repo](https://img.shields.io/github/stars/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App?color=yellow&style=social)](https://github.com/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App/stargazers)

## AI-Powered Waste Classification for a Greener Planet

EcoSnap is a revolutionary mobile application that leverages cutting-edge AI image recognition to instantly classify waste items. It provides users with clear, actionable guidance on recycling, composting, or landfill disposal, fostering responsible waste management habits.

<details>
<summary>🤖 <b>AI AGENT DIRECTIVES</b></summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript/JavaScript - React Native)**
    *   **Stack:** This project leverages **TypeScript 6.x** for type safety and maintainability. The core framework is **React Native 0.75+**, managed with **Expo 51+** for streamlined development and deployment across iOS and Android. For rapid linting and formatting, **Biome 15+** is integrated.
    *   **Architecture:** Adheres to a **Feature-Sliced Design (FSD)** pattern, promoting modularity, testability, and scalability. Key architectural components include `entities`, `features`, `widgets`, `pages`, and `shared` layers.
    *   **State Management:** Employ **Signals** (standardized via a library like Preact Signals or similar) for efficient, fine-grained state updates across the application.
    *   **AI Integration:** Utilizes a **Cloud-based AI Service API** (e.g., Google Cloud Vision AI, AWS Rekognition, or a custom model endpoint) for image analysis. Implement robust error handling, request throttling, and consider offline fallback mechanisms.
    *   **UI/UX:** Focus on modern, accessible, and performant UI/UX patterns. **Tailwind CSS v4** (via native-wind or similar for React Native) for utility-first styling. Leverage native platform UI components where beneficial.

### 4. VERIFICATION & TESTING PROTOCOL
*   **Unit Testing:** **Vitest 2+** with **React Testing Library** for comprehensive unit and component testing.
*   **End-to-End (E2E) Testing:** **Playwright 1.40+** for cross-platform E2E validation on simulators/emulators and real devices.
*   **Linting & Formatting:** **Biome 15+** enforces code style and catches potential errors early.
*   **Continuous Integration:** GitHub Actions for automated builds, testing, and deployment pipelines.

### 5. DEVELOPMENT WORKFLOW & STANDARDS
*   **Version Control:** Git, hosted on GitHub.
*   **Commit Messages:** Conventional Commits standard.
*   **Code Quality:** Adhere to **SOLID**, **DRY**, and **YAGNI** principles.
*   **Dependency Management:** Managed via Expo/npm/yarn.

</details>

## 🚀 Features

*   **Instant Waste Identification:** Snap a photo, and EcoSnap instantly identifies the item using AI.
*   **Smart Disposal Guidance:** Get clear instructions on whether to recycle, compost, or send to landfill.
*   **Detailed Information:** Access comprehensive data on materials, recycling processes, and environmental impact.
*   **Personal History:** Track your waste disposal history and monitor your environmental contribution.
*   **Cross-Platform:** Native performance and user experience on both iOS and Android.

## 🌳 Architecture

EcoSnap employs a Feature-Sliced Design (FSD) architecture to ensure maintainability, scalability, and testability. The core components are organized into distinct layers:

ascii
EcoSnap-AI-Waste-Classification-Mobile-App
├── entities/
│   └── waste-item/
├── features/
│   ├── camera/
│   ├── image-classification/
│   └── disposal-guidance/
├── widgets/
│   ├── history-list/
│   └── item-details/
├── pages/
│   ├── CameraPage.tsx
│   ├── ClassificationResultPage.tsx
│   └── HistoryPage.tsx
├── app/
│   ├── App.tsx
│   └── navigation/
└── shared/
    ├── ui/
    ├── api/
    └── utils/


## 📦 Tech Stack

*   **Mobile Framework:** React Native with Expo
*   **Language:** TypeScript
*   **AI/ML:** Cloud-based Vision API (e.g., Google Cloud Vision AI, AWS Rekognition)
*   **Styling:** Tailwind CSS (via native-wind or similar)
*   **State Management:** Signals
*   **Linting & Formatting:** Biome
*   **Testing:** Vitest (Unit), Playwright (E2E)
*   **CI/CD:** GitHub Actions

## 🛠️ Development Setup

### Prerequisites

*   Node.js (LTS version recommended)
*   Expo CLI
*   `git` command-line tool

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/EcoSnap-AI-Waste-Classification-Mobile-App.git
    cd EcoSnap-AI-Waste-Classification-Mobile-App
    

2.  **Install dependencies:**
    bash
    npx expo install
    
    *(If `npx expo install` fails, try `npm install` or `yarn install` depending on your package manager setup)*

3.  **Configure Environment Variables:**
    Create a `.env` file in the root directory and add your API keys:
    env
    EXPO_PUBLIC_VISION_API_KEY=YOUR_CLOUD_VISION_API_KEY
    # Add other necessary environment variables here
    

### Running the App

*   **Start the development server:**
    bash
    npx expo start
    

*   **Run on a simulator/emulator or physical device:**
    Follow the instructions printed in your terminal after running `npx expo start` to open the app on iOS Simulator, Android Emulator, or your physical device via the Expo Go app.

## 📜 Scripts

| Script        | Description                                                     |
| ------------- | --------------------------------------------------------------- |
| `start`       | Starts the Expo development server.                             |
| `android`     | Builds and runs the app on an Android emulator/device.          |
| `ios`         | Builds and runs the app on an iOS simulator/device.             |
| `lint`        | Runs Biome for linting and formatting checks.                   |
| `format`      | Auto-formats code using Biome.                                  |
| `test:unit`   | Runs unit tests using Vitest.                                   |
| `test:e2e`    | Runs end-to-end tests using Playwright.                         |
| `build:apk`   | Builds a standalone Android APK.                                |
| `build:app`   | Builds a standalone iOS application archive.                    |

## 🌟 Development Principles

We adhere to industry-leading development principles to ensure code quality, maintainability, and scalability:

*   **SOLID:** Design principles for robust and maintainable object-oriented software.
*   **DRY (Don't Repeat Yourself):** Avoid duplication of logic and data.
*   **YAGNI (You Ain't Gonna Need It):** Implement only necessary functionality; avoid over-engineering.
*   **FSD (Feature-Sliced Design):** Promotes modularity and separation of concerns in the codebase.

--- 

### Contributing

Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0) - see the [LICENSE](LICENSE) file for details.

### Security

See our [SECURITY.md](SECURITY.md) for details on reporting security vulnerabilities.
