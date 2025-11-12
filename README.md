# BonusProject – Firebase Auth with Email & GitHub

This project is a React Native (Expo) application that implements secure
authentication using **Firebase Email/Password** and **GitHub OAuth**.

It includes:
- Email login & registration
- GitHub login with provider checks
- GitHub linking to an existing Email account
- Error messages displayed inside the UI
- Protected routes via Expo Router
- Firebase Web SDK integration

---

## 🚀 Features

### 🔐 Authentication
- Sign in with **Email & Password**
- Sign in with **GitHub**
- Block GitHub login if the email already exists as an Email/Password account
- Link GitHub to an existing email account (inside home screen)
- Auto-hide GitHub link button when linked
- Clean inline error UI (instead of alerts)

### 🛡 Security
- Firebase Auth Providers
- Prevent unwanted GitHub account linking
- Session clearing on login screen
- GitHub Client Secret stored securely (NOT committed to GitHub)

---

## 📦 Tech Stack

- **React Native (Expo)**
- **Firebase Authentication**
- **Expo Router**
- **JavaScript**
- **GitHub OAuth Web Flow**

---

## 📁 Project Structure

