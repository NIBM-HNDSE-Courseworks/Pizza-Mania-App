# 🍕 Pizza Mania App

**A comprehensive Android-based Pizza Ordering & Management System.**

> **Pizza Mania** is a multi-role mobile application designed to streamline the entire pizza ordering process. From a customer craving a slice to the admin managing branches, employees processing orders, and deliverymen ensuring timely arrival—this app connects them all.

---

## 📱 Features & Workflows

### 👤 For Customers
* **Interactive Menu:** Browse pizzas, burgers, and drinks by category.
* **Smart Cart:** Add items, customize quantities, and view total costs instantly.
* **AI Chatbot:** A built-in assistant to help with queries or navigation.
* **Order Tracking:** View active orders and browse past order history.
* **Branch Locator:** Find the nearest Pizza Mania branch using the Map integration.

### 🛡️ For Admins
* **Menu Management:** Add, edit, or remove menu items and categories.
* **Branch & Staff Control:** Manage physical branch locations and hire/fire employees.
* **Fleet Management:** Oversee delivery personnel and assign resources.

### 👨‍🍳 For Employees (Kitchen/Staff)
* **Order Dashboard:** Receive incoming orders in real-time.
* **Status Updates:** Update order stages (Preparing, Ready, etc.).
* **History:** View logs of completed orders for the shift.

### 🛵 For Deliverymen
* **Delivery Queue:** View assigned orders ready for dispatch.
* **Live Map Navigation:** Real-time map view showing the deliveryman's current location relative to the customer's delivery address.
* **Delivery History:** Track completed deliveries.

---

## 📸 App Showcase

### 🟢 Customer Experience
Everything a user needs to order their favorite meal.

| **Menu & Browsing** | **Smart Cart** |
|:---:|:---:|
| <img width="431" height="944" alt="Customer Menu Interface" src="https://github.com/user-attachments/assets/f28c1a3e-2548-4700-bd07-142057bc014a" /> | <img width="425" height="941" alt="Shopping Cart View" src="https://github.com/user-attachments/assets/eec6d36c-2cce-42d7-8eb8-bdc5d4986a7f" /> |
| *Browse categories and items* | *Review items and checkout* |

| **AI Chatbot Assistant** | **Order History** |
|:---:|:---:|
| <img width="427" height="940" alt="AI Chatbot Interface" src="https://github.com/user-attachments/assets/8867fa82-b0bb-46e3-9bb9-f5ce7ad6a161" /> | <img width="425" height="939" alt="Customer Order History" src="https://github.com/user-attachments/assets/8ce2a33a-f972-46b2-8f38-6b4f3329ad82" /> |
| *Get help instantly* | *Track past delicious meals* |

---

### 🔴 Admin Dashboard
Complete control over the business operations.

| **Menu Management** | **Branch & Staff Ops** | **Delivery Fleet** |
|:---:|:---:|:---:|
| <img width="424" height="941" alt="Admin Menu Management" src="https://github.com/user-attachments/assets/68241841-32f2-4d06-bc0b-313b06fe1940" /> | <img width="428" height="937" alt="Admin Branch Management" src="https://github.com/user-attachments/assets/04f10ae5-c036-4a78-a1a8-0ed0edf7210a" /> | <img width="422" height="938" alt="Admin Deliveryman Management" src="https://github.com/user-attachments/assets/93a0c9aa-13f4-496d-8f38-f1bde3e78e4e" /> |
| *Add/Edit Pizzas* | *Manage Branches & Staff* | *Oversee Deliverymen* |

---

### 🔵 Staff & Logistics
Tools for the people on the ground.

| **Employee: Order Management** | **Employee: History** |
|:---:|:---:|
| <img width="430" height="940" alt="Employee Order Dashboard" src="https://github.com/user-attachments/assets/2be8d227-c931-47ea-bdc7-91194ccda174" /> | <img width="427" height="927" alt="Employee Order History" src="https://github.com/user-attachments/assets/aa10bb13-96ac-4380-8c26-a714187a29b4" /> |
| *Process incoming orders* | *View completed tasks* |

| **Deliveryman: Active Deliveries** | **Deliveryman: History** |
|:---:|:---:|
| <img width="422" height="935" alt="Deliveryman Active Orders" src="https://github.com/user-attachments/assets/d4d42845-626e-4fd7-af00-65b38791681f" /> | <img width="428" height="937" alt="Deliveryman Delivery History" src="https://github.com/user-attachments/assets/78c489dc-9065-40b5-a834-efd68f543e8f" /> |
| *Orders to deliver* | *Completed runs* |

---

## 🛠 Tech Stack

* **Language:** Java / Kotlin
* **Frontend:** Android XML Layouts
* **Backend / Database:** **Firebase** (Core Database, Auth & Realtime Data)
* **Local Storage:** **SQLite** (Minor profile management & caching)
* **Architecture:** MVC (Model-View-Controller)
* **Tools:** Android Studio, Gradle

---

## 📂 Project Structure

The app is organized into distinct packages for logic and data handling:

* `com.example.pizzamaniaapp` - Core activities and logic.
* `com.example.pizzamaniaapp.models` - Data classes (User, Item, Order, Branch).
* `com.example.pizzamaniaapp.adapters` - Adapters for RecyclerViews (Menu, Orders, Chat).
* **Database Helpers:** Dedicated classes for handling SQLite operations for Admin and User profiles.
