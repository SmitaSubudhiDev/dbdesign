# 🛗 Smart Elevator Control System – ER Diagram

## 📌 Problem Statement
LiftGrid Systems builds intelligent elevator control platforms for large commercial buildings such as corporate towers, malls, airports, hospitals, and high-rise residential complexes. These environments contain multiple elevators operating across many floors and serving thousands of passengers daily.

The system must efficiently manage elevator assignments, track floor requests, monitor elevator status, log ride activity, and handle maintenance operations across multiple buildings.

---

## 🎯 Objectives
This database design aims to support:

- Multiple buildings management  
- Multiple elevators per building  
- Floor-level request tracking  
- Elevator assignment logic  
- Ride history logging  
- Elevator status monitoring  
- Maintenance tracking  
- Analytics-ready ride data  
- Scalable infrastructure for high-rise buildings  

---

## 🧩 Entities Included

| Entity | Description |
|--------|-------------|
| Buildings | Stores building information |
| Floors | Floors belonging to a building |
| Zones | Segment floors into zones |
| Elevator Groups | Group of elevators in a building |
| Elevators | Elevator details |
| Elevator Floor Map | Many-to-many elevator-floor mapping |
| Floor Requests | User-generated requests |
| Ride Assignments | Elevator assigned to request |
| Ride Logs | Completed ride history |
| Elevator Status | Status history tracking |
| Maintenance Types | Maintenance category |
| Maintenance Logs | Elevator maintenance history |

---

## 🔗 Relationships

- One building has many floors  
- One building has many elevators  
- One building has multiple zones  
- One building has multiple elevator groups  
- Elevators belong to groups  
- Elevators serve multiple floors  
- Floors can be served by multiple elevators  
- Floor requests originate from floors  
- Each request is assigned to one elevator  
- Elevators complete multiple rides  
- Elevator status tracked over time  
- Maintenance history tracked per elevator  

---

## 🚀 Key Features

- Multi-building support  
- High-rise zone segmentation  
- Elevator grouping (bank system)  
- Request priority handling  
- Ride analytics ready  
- Status history tracking  
- Maintenance tracking  
- Scalable architecture  

---

## 📊 Design Considerations

- Dynamic ride data separated from elevator configuration  
- Status stored as history (not overwritten)  
- Many-to-many mapping for elevator-floor support  
- Maintenance stored separately for audit tracking  
- Request and ride lifecycle separated  

---

## 📈 Supported Queries

This design can answer:

- How many buildings exist?  
- How many elevators per building?  
- Which elevator serves which floors?  
- Which requests are pending?  
- Which elevator handled most rides?  
- How many rides completed today?  
- Which elevator is under maintenance?  
- Maintenance history per elevator  
- Ride analytics and performance tracking  

---

## 🏁 Conclusion
This ER design provides a scalable and production-ready database structure for managing intelligent elevator control systems across multiple large buildings. It supports real-time ride allocation, monitoring, analytics, and maintenance tracking.