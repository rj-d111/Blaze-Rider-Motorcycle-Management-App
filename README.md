# Blaze-Rider-Motorcycle-Management-App
Blaze Rider is created using Java, Kotlin -- a mobile application designed for motorcycle riders to manage rides, connect with other riders, and stay updated with weather alerts and announcements. It integrates Google Maps for Navigation and offers a community-driven experience through ride sharing and social features.     


# 🏍️ Blaze Rider – Motorcycle Management App

Blaze Rider is a mobile application designed for motorcycle riders to **manage rides, connect with other riders, and stay updated** with weather alerts and announcements.  
The app integrates **Google Maps** for navigation and offers a **community-driven** experience through ride sharing and social features.

---

## 📖 Table of Contents
1. [Overview](#-overview)
2. [Features](#-features)
3. [Tech Stack](#-tech-stack)
4. [User Roles](#-user-roles)
5. [App Navigation Flow](#-app-navigation-flow)
6. [Screenshots](#-screenshots)
7. [Future Improvements](#-future-improvements)
8. [Developer](#-developer)

---

## 📱 Overview

Blaze Rider helps riders:
- Plan and navigate rides using **Google Maps integration**  
- **Share rides** and travel together with other riders  
- Receive **real-time weather notifications**  
- Stay informed with **announcements and news feeds**  
- Manage accounts and profiles securely  

---

## 🚀 Features

### 🗺️ 1. Home Page – Search Location & Weather Notification
- Riders can **search for destinations** using Google Maps integration.  
- Displays **estimated distance and travel time** for two-wheelers.  
- Sends **automatic weather notifications** for the current and destination locations.  
- Provides quick access to **start navigation** or **share routes** with others.

**Key Functions:**
- Google Maps API integration  
- Weather API integration  
- Real-time notification system  

---

### 🤝 2. Shared Rides Page
- When users tap **“Share Ride”**, this page shows all **available shared rides**.  
- Each ride displays:
  - Rider’s name  
  - Origin and destination  
  - Distance and duration  
- Riders can **Preview** the route or **Join** the ride to follow others.

**Key Functions:**
- Create and join shared rides  
- Route preview integration  
- Real-time ride updates  

---

### 📢 3. Announcements Page
- Managed by **admins** to post important updates or upcoming events.  
- Riders can **like** or **comment** on announcements.  
- Ideal for sharing **group ride events**, **safety reminders**, or **community news**.

**Key Functions:**
- Admin post creation  
- Likes and comments  
- Event notifications  

---

### 🏍️ 4. News Feed Page
- A community feed where riders can **share posts, thoughts, and experiences**.  
- Supports **likes, comments, and sharing** to build rider connections.

**Key Functions:**
- User-generated content  
- Reactions and comments  
- Rider community interaction  

---

### 🔔 5. Notifications Page
- Displays all **weather-related notifications** for the rider’s saved or active locations.  
- Each notification includes:
  - Location coordinates  
  - Weather conditions  
  - Temperature  
  - Timestamp  

**Key Functions:**
- Weather alerts  
- Location-based updates  
- “Mark all as read” feature  

---

### ⚙️ 6. More Page (Profile & Settings)
- Riders can manage their account with options to:
  - **Edit Profile**
  - **Change Password**
  - **Logout**
- Displays user information like name and email.

**Key Functions:**
- Profile management  
- Secure password handling  
- Logout functionality  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | Flutter / React Native |
| **Backend** | Firebase / Node.js / Express |
| **Database** | Firestore / MongoDB |
| **APIs** | Google Maps API, OpenWeather API |

---

## 🔒 User Roles

| Role | Description |
|------|--------------|
| **Admin** | Can post announcements and manage updates. |
| **Rider/User** | Can search rides, share routes, view weather, and engage with posts. |

---

## 🗂️ App Navigation Flow

| Page | Accessed From | Description |
|------|----------------|-------------|
| **Home** | Default screen | Search rides, view routes, and weather notifications |
| **Shared Rides** | Share Ride button | Browse and join shared rides |
| **Announcements** | Bottom navigation | View admin posts and event updates |
| **News Feed** | Bottom navigation | Post and engage with other riders |
| **Notifications** | Bottom navigation | View weather alerts and location data |
| **More** | Bottom navigation | Manage profile, change password, logout |

---

## 📸 Screenshots

1. 🗺️ Home Page – Search & Weather Notifications  
2. 🤝 Shared Rides Page  
3. 📢 Announcements Page  
4. 🏍️ News Feed Page  
5. 🔔 Notifications Page  
6. ⚙️ More Page (Profile & Settings)

*(Attach your screenshots in the `/screenshots` folder and embed them here using Markdown images)*

Example:
```markdown
![Home Page](screenshots/home.jpg)
![Shared Rides](screenshots/shared_rides.jpg)
