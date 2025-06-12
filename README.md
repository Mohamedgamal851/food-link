# 🍽️ Food Donation Platform

A full-stack web application that connects food donors with charities to reduce food waste and support communities in need. The system ensures efficient management of surplus food items and enables real-time interaction between donors and charities.

## 🔧 Tech Stack

Frontend: React.js
Backend: Node.js & Express
Database: MySQL
Authentication: JWT (JSON Web Tokens)
HTTP Client: Axios


## ✨ Key Features

## 🔐 Role-Based Login & Registration

Separate access for food donors and charities
JWT-secured authentication


## 🍱 Donor Features

1. Register surplus food items with type, quantity, and expiration.
2. Track food item status: Available, Fulfilled, Canceled.
3. View charity requests and manage donated food inventory.


## ❤️ Charity Features

1. Browse available food items added by donors.
2. Request specific quantities and view the live status of each meal.


## 📊 Real-Time Metrics

Dynamic Counters: Display live statistics including:

Total meals donated
Number of supported charities
Meals in fulfillment status


## 🛠️ Implementation Details

## 🔁 State Management & Routing

React Hooks: useState, useEffect, useContext
Routing: Secure navigation using HashLink


## 🔌 Communication

Axios is used for seamless data transfer between the frontend and backend.
