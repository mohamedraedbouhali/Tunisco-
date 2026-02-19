# Tunisco: The Ultimate Tunisian Travel Companion

**Tunisco**  is a comprehensive, full-stack web application designed to revolutionize the way tourists explore Tunisia 🇹🇳.

From the historic streets of Carthage 🏛️ to the golden dunes of the Sahara 🏜️, Tunisco provides a seamless interface for travelers to discover vibrant cities 🏙️, explore local businesses 🛍️, and manage their journey with ease 📍.

---

## 📖 Project Overview

Traveling through Tunisia can be an overwhelming experience due to its rich, multi-layered history. **Tunisco** was built to solve the fragmentation of travel information. It provides a structured, city-by-city guide focusing on authenticity, ease of booking, and local insights.

### The Problem vs. The Solution
* **The Gap:** Many local Tunisian restaurants and boutique hotels (Dars) lack a centralized, user-friendly digital booking presence.
* **The Fix:** A unified platform where users can explore "Experience Hubs" for each city and manage their journey via a custom-built PHP reservation engine.

---

## ✨ Key Features

### 🏛️ City Discovery Modules
Interactive profiles for major destinations including **Tunis, Sousse, Djerba, Tozeur, and Bizerte**.
* **Historical Context:** Brief, curated snippets about city heritage.
* **Weather Integration:** (Planned) Real-time climate data contrast for Saharan vs. Coastal trips.

### 🏨 Business Directory & Reservations
* **Smart Filtering:** Find restaurants by cuisine (e.g., Traditional vs. Mediterranean) or hotels by star rating.
* **Dynamic Booking Logic:** A PHP-driven system that prevents overbooking by performing real-time availability checks in the MySQL database.
* **User Dashboard:** (In Progress) A private space to view and manage upcoming reservations.

### 📱 Modern UX/UI
* **Responsive Grid:** Tailored layouts for mobile travelers on the go.
* **Asynchronous Loading:** Uses the **JavaScript Fetch API** for smooth page transitions without full browser reloads.

---

## 🛠️ Technical Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Custom Variables), Vanilla JavaScript |
| **Backend** | PHP (Procedural/OOP Hybrid) |
| **Database** | MySQL (Relational Schema) |
| **Security** | Password Hashing, SQL Injection Prevention (Prepared Statements) |

---

## 📂 Repository Structure

```text
├── assets/         # Optimized images, icons, and branding
├── css/            # Modular stylesheets (main.css, responsive.css)
├── js/             # Form validation and asynchronous UI logic
├── includes/       # PHP partials (db_connection, header, footer)
├── auth/           # User authentication and session logic
├── database/       # .sql exports for environment setup
└── index.php       # Main application entry point
