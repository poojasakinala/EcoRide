
# 🚲 Eco Ride

**Eco Ride** is a modern, sustainable, and secure ride-hailing Android application. Designed using **Jetpack Compose**, it leverages the latest in mobile technology to provide a clean UI/UX, real-time ride discovery with **Google Maps**, seamless **Razorpay** integration, and robust **driver verification** via **Firebase**.

---

## 🌟 Features

### 🔐 Multi-Authentication System

Log in using:

* Username & Password
* Google Account
* Facebook
* Mobile Number (OTP-based)

### 📍 Real-time Ride Discovery with Google Maps

* Locate nearby rides on an interactive map
* Live location updates and routing suggestions
* Accurate pickup & drop-off location handling

### 💳 Razorpay Payment Integration

* Secure & seamless in-app payments
* View transaction history and confirmations
* Razorpay Checkout SDK for fast payments

### ✅ Driver Verification Module

* Upload documents for verification:

  * Address Proof
  * Driving License
  * Vehicle Registration Certificate (RC)
* Documents stored securely via **Firebase Cloud Storage**

---

## 🖼️ UI Screenshots

Place your screenshots inside the `/screenshots` folder.
Reference them as shown below:

> ![Login Screen](https://github.com/poojasakinala/EcoRide/blob/26238eb5003d3ead98228778b28e9643ff1818c4/01.jpg)
> ![Ride Finder](./screenshots/maps_screen.png)


---

## 🛠️ Tech Stack

| Layer        | Technologies Used                             |
| ------------ | --------------------------------------------- |
| **Language** | Kotlin                                        |
| **UI**       | Jetpack Compose                               |
| **Backend**  | Firebase (Authentication, Firestore, Storage) |
| **Payment**  | Razorpay Checkout SDK                         |
| **Maps**     | Google Maps SDK                               |
| **IDE**      | Android Studio (Hedgehog or later)            |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/eco-ride.git
```

### 2. Open the Project in Android Studio

* Launch **Android Studio**
* Select **Open** and navigate to the cloned project folder

### 3. Configure API Keys

Add the following configuration files:

| File                                        | Purpose                |
| ------------------------------------------- | ---------------------- |
| `google-services.json`                      | Firebase configuration |
| `local.properties` or `AndroidManifest.xml` | Google Maps API Key    |
| `BuildConfig` or `.env`                     | Razorpay API Key       |

> ⚠️ **Never commit your API keys. Use `.gitignore` and secure storage methods.**

---

## 📁 Project Structure

```
EcoRide/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/ecoride/
│           │   ├── ui/         # Jetpack Compose Screens
│           │   ├── data/       # Firebase & API integrations
│           │   └── utils/      # Helper classes and extensions
├── screenshots/
│   ├── login_screen.png
│   ├── maps_screen.png
│   └── payment_screen.png
├── build.gradle
└── README.md
```

---

## 🧾 Requirements

* Android Studio **Hedgehog | Iguana** (2024+)
* Kotlin **1.9+**
* Jetpack Compose **1.6+**
* Firebase Project with:

  * Authentication (Email, Google, Facebook, Phone)
  * Firestore / Realtime Database
  * Firebase Storage
* Razorpay Developer Account
* Google Cloud Maps API Key

---



> *“Eco Ride – Drive Clean, Ride Green.”* 🌱


