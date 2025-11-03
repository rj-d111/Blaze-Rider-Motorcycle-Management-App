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

![Screenshot_2025-11-03-11-01-30-89_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/0c9c364b-aec0-45f8-a538-8d8fb3617aab)

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
![Screenshot_2025-11-03-11-01-39-48_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/5cf67be4-5627-4e8f-9619-e8237967bc98)

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
![Screenshot_2025-11-03-10-59-32-93_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/e0a11ac5-7330-4eda-98c9-12871c269c4f)


### 📢 3. Announcements Page
- Managed by **admins** to post important updates or upcoming events.  
- Riders can **like** or **comment** on announcements.  
- Ideal for sharing **group ride events**, **safety reminders**, or **community news**.

**Key Functions:**
- Admin post creation  
- Likes and comments  
- Event notifications  

---
![Screenshot_2025-11-03-10-59-37-81_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/954ea4e0-b4bd-4af4-b7ef-69f23199f851)

### 🏍️ 4. News Feed Page
- A community feed where riders can **share posts, thoughts, and experiences**.  
- Supports **likes, comments, and sharing** to build rider connections.

**Key Functions:**
- User-generated content  
- Reactions and comments  
- Rider community interaction  

---
![Screenshot_2025-11-03-10-59-40-98_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/8c8ec00f-cb46-462f-93e4-0410a4878eb7)

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
![Screenshot_2025-11-03-10-59-49-37_6913fe7be745fdc815ee4ec6a594a735](https://github.com/user-attachments/assets/5d957613-fadc-4d29-ab3d-8c3adcffb1d5)

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

