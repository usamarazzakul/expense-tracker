# Expense Tracker

Welcome to the official release repository for **Expense Tracker**. This repository is dedicated exclusively to distributing the latest release APK for users who want to manage their personal finances seamlessly.

*Please note: The source code is closed-source and not hosted in this repository.*

---

## 📱 About the App

**Expense Tracker** is a feature-rich, offline-first Android application designed to help you take complete control of your personal finances. With an intuitive and glassy UI, the app provides tools to track daily expenses, plan upcoming bills, achieve savings goals, and analyze your financial habits.

## ✨ Key Features

### 💸 Finance Management
*   **Income & Expense Logging:** Quickly record your financial transactions with a dedicated quick-action dashboard.
*   **Custom Categories:** Organize your spending using built-in categories (e.g., Food, Transport, Salary) or create your own custom categories.
*   **Recurring Transactions:** Automate your repeating bills and income (Daily, Weekly, Monthly, or Yearly).
*   **Savings Goals:** Set specific financial targets, allocate funds, and track your completion percentage visually.

### 🛠️ Built-in Productivity Tools
*   **Shopping (Bazaar) List:** Create checklists for shopping, estimate total costs, and instantly convert checked items into an expense.
*   **Smart Calculator:** Perform calculations on the fly, view calculation history, and save important calculation sessions for later reference.
*   **Personal Notes:** Keep track of your financial thoughts or important reminders in the dedicated "My Notes" section.
*   **Calendar & Planner:** View your daily insights, income, expenses, and net balance directly from a calendar view.

### 📊 Analytics & Data Security
*   **Financial Summaries:** View monthly and all-time net balance overviews, alongside breakdown charts for expenses by category.
*   **Export to CSV:** Export your categorized financial data to a CSV file for external spreadsheet analysis.
*   **Backup & Restore:** Securely backup your offline data and restore it whenever you switch devices.

### ⚙️ Customization & Accessibility
*   **Multi-Language Support:** Fully localized in English, Bengali (বাংলা), and Hindi (हिंदी).
*   **Theming:** Toggle between Light Mode, Dark Mode, or follow your system's default theme.
*   **Smart Reminders:** Enable daily logging reminders, shopping list nudges, and upcoming expense/income notifications.

---

## 🚀 How to Install (APK)

Since this repository only hosts the release application, you can install it directly on your Android device:

1.  Navigate to the **[Releases](../../releases)** tab of this repository.
2.  Download the latest `app-release.apk` file to your Android device.
3.  Open the downloaded APK file.
4.  *Note: If prompted, you may need to enable **"Install from Unknown Sources"** in your device's security settings.*
5.  Follow the on-screen instructions to complete the installation and launch **Expense Tracker**.

---

## 🛠️ Technical Overview

While the source code is private, the application is built utilizing modern Android development standards:
*   **Language:** Java / Android SDK
*   **Architecture:** UI mapped through XML layouts utilizing Material Components (`MaterialCardView`, `FloatingActionButton`, `BottomNavigationView`)
*   **Local Database:** Room Database / SQLite for secure, offline data persistence (`AppDatabase`, `TransactionDao`, `CategoryDao`)
*   **Background Processing:** Android `WorkManager` for handling daily notifications and scheduled reminders
*   **Monetization & Ads:** Google AdMob integration (App Open Ads, Interstitial, and Rewarded Ads for premium features like data backup)

---

## 📸 Screenshots

*(You can upload your screenshots to an `assets` folder and link them here)*

| Home Dashboard | Add Transaction | Financial Summary | Savings Goals |
| :---: | :---: | :---: | :---: |
| <img src="home_ss.png" width="200"/> | <img src="add_ss.png" width="200"/> | <img src="summary_ss.png" width="200"/> | <img src="goals_ss.png" width="200"/> |

---

## 🤝 Support & Contact

If you encounter any bugs, have feature requests, or need general support, please feel free to open an **Issue** in this repository.

*   **Developer:** Usama Razzakul Islam (Softbondit)
*   **Email:** usamarazzakul@gmail.com
*   **Phone:** +8801305359586

---
*© 2026 Usama Razzakul Islam / Softbondit. All rights reserved.*
