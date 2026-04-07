# 🏋️ Fitness Coaching Platform – ER Diagram Design

This project contains a **database design** for an online fitness coaching platform where trainers/influencers manage clients, sell coaching plans, schedule sessions, and track progress.

---

## 📌 Problem Statement

A fitness influencer runs an online coaching business. The system should support:

- Trainer and client management  
- Coaching plans and subscriptions  
- Consultation and live sessions  
- Client progress tracking  
- Weekly check-ins  
- Payments and subscriptions  
- Diet and workout plan assignment  

This is **not a gym management system**, but an **online coaching ecosystem**.

---

## 🗂️ Entities Included

### 👤 User & Roles
- staff  
- trainers  
- clients  
- trainers_clients  

### 📦 Plans & Subscriptions
- plans  
- subscriptions  

### 💳 Payments
- payments  

### 📈 Progress Tracking
- progress  
- body_measurements  
- check_in  

### 📅 Sessions
- sessions  

### 🥗 Plan Content
- diet_plan  
- workout_plans  

---

## 🔗 Key Relationships

- One trainer can handle multiple clients  
- One client can subscribe to multiple plans  
- One plan can be purchased by many clients  
- Each subscription tracks start and end dates  
- Payments are linked to subscriptions  
- Trainers schedule sessions with clients  
- Clients submit check-ins and progress updates  
- Diet and workout plans belong to a coaching plan  

---

## 🎯 Purpose

This ER diagram helps structure a scalable **online fitness coaching platform** with proper separation of users, subscriptions, sessions, and progress tracking.