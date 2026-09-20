# NexusFlow — B.Com Commerce & Auditing AI Suite

**NexusFlow** is an intelligent, modern study platform and auditing assistant engineered exclusively for **B.Com (Bachelor of Commerce)** students and commerce scholars. It integrates curriculum-aligned auditing modules, practice case study simulations, a context-aware Gemini AI chatbot with faculty doubt-clearing bookings and diagnostic troubleshooting, interactive flashcards, real-time study notifications, and an eye-safe dark theme.

---

## 🌟 Key Features

### 1. 🎓 Exclusively for B.Com Commerce Students
- **Curriculum-Aligned Syllabus:** Structured specifically for B.Com Semester V & VI Auditing & Assurance papers (e.g. Unit I to V: Principles of Auditing, Internal Check & Control, Vouching & Verification, Company Audit under Companies Act 2013, and Audit Reports / Standards on Auditing).
- **University Profiles:** Student account creation with college/university affiliation, semester tracking, and targeted examination syllabus options.

### 2. 🤖 Context-Aware Gemini AI Assistant
- **Multi-Turn Context:** Remembers discussion context across conversation turns for coherent academic guidance and multi-step tasks.
- **Multi-Step Faculty Booking Flow:** Step-by-step interactive workflow to schedule 1-on-1 doubt clearing, practical file review, or viva mock sessions with commerce professors.
- **Audit Troubleshooting Diagnostics:** Diagnostic troubleshooting engine for balancing cash transactions, vouchers, cutoff testing, and statutory compliance hurdles.
- **One-Click Flashcard Saving:** Directly convert AI explanations and legal standard citations into reviewable flashcards.

### 3. 🌙 Dark Mode (Tailwind Slate Theme)
- **Persistent Theme Switching:** Seamless dark/light toggle accessible from the top navigation bar, the user profile dropdown, and app preferences.
- **Fintech/EdTech Color Palette:** Deep Slate-900 background, crisp Slate-800 surfaces, high-contrast typography, and vibrant Emerald-500 accent highlights.

### 4. 🔔 Real-Time Notification System
- **Header Alert Bell:** Notification bell in the header displaying a live badge with unread counts.
- **Notifications Modal:** Interactive sheet categorizing alerts into New Module Releases, Assignment Deadlines, 1-on-1 Faculty Booking Confirmations, and University Exam Advisories.
- **Real-Time Integration:** Faculty session bookings confirmed in the chat immediately generate active notifications and increment unread counts.

### 5. 🔐 User Authentication & Session Security
- **B.Com Sign-In & Sign-Up:** Secure student registration with full name, college, target semester, and password.
- **1-Click Instant Demo Accounts:** Fast access via pre-configured mock B.Com scholars (Priya - Sem V, Rohan - Sem VI, Ananya - Sem IV).
- **Session Tokens:** Generates SHA-256 session tokens with mock persistence across app reloads.

---

## 🛠️ Technology Stack

- **Language:** 100% Kotlin
- **UI Framework:** Jetpack Compose with Material Design 3 (M3)
- **Architecture:** MVVM / Unidirectional Data Flow with clean reactive state management
- **Theme:** Dynamic Material 3 with customized Slate & Emerald palette
- **AI Integration:** Google Gemini API (gemini-2.5-flash) with server-side proxy support
- **Persistence:** Android SharedPreferences for session and theme state

---

## 🚀 Getting Started

### Prerequisites
- Android Studio Hedgehog or newer
- JDK 17+
- Android SDK 34 (API Level 34)

### Building the Project
Clone the repository and run Gradle:
```bash
gradle assembleDebug
```

### Launching on Device/Emulator
Open the project in Android Studio and select **Run > Run 'app'** or install via Gradle:
```bash
gradle installDebug
```

---

## 📜 License
Developed for educational excellence in B.Com commerce education.
