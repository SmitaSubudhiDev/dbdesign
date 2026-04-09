# 🅿️ Comic-Con Multi-Zone Parking System – Database Design

This project contains a database design for a large event parking system used in venues like Comic-Con India. The system manages vehicle entry, parking spot allocation, EV charging, reservations, multi-day events, and payments.

---

## 📌 Problem Statement

A large convention venue hosts a multi-day event with thousands of visitors arriving using different vehicle types. The parking facility has multiple zones and levels, reserved areas, EV charging spots, and special access for VIPs, exhibitors, staff, and cosplayers.

The system should track:
- Vehicles entering the facility
- Vehicle categories
- Parking spot allocation
- Reserved parking categories
- Entry and exit timestamps
- Parking sessions
- Ticket generation
- Payment status
- Spot availability across zones and levels
- Multi-day event parking
- EV charging usage
- Advance reservations

---

## 🧱 Entities Included

- vehicles  
- vehicle_categories  
- access_categories  
- events  
- parking_zones  
- parking_levels  
- parking_spots  
- parking_spot_categories  
- reservations  
- parking_sessions  
- parking_tickets  
- payments  
- ev_charging_sessions  
- parking_rates  
- staff  

---

## 🔗 Key Relationships

- One vehicle can have multiple parking sessions
- One parking spot can be reused across sessions
- Parking zones contain multiple levels
- Parking levels contain multiple spots
- Reservations link vehicles to spots for specific events
- Parking sessions track entry and exit times
- Payments are linked to parking sessions
- EV charging sessions extend parking sessions
- Staff records entry and exit handling
- Events allow multi-day tracking

---

## ✨ Features Supported

✔ Multi-zone parking system  
✔ Multi-level parking structure  
✔ Reserved parking (VIP, staff, exhibitors)  
✔ EV charging spot management  
✔ Parking ticket generation  
✔ Entry & exit timestamp tracking  
✔ Payment tracking  
✔ Spot availability tracking  
✔ Multi-day event support  
✔ Advance reservation system  
✔ Staff handling tracking  
✔ Dynamic parking rates  

---

## 📊 Questions This Design Can Answer

- What vehicles entered the facility?
- Which parking spot was assigned?
- Which zone and level was used?
- Was the spot reserved?
- When did the vehicle enter and exit?
- Can a vehicle visit multiple times?
- Can a spot be reused?
- Which vehicles are currently parked?
- How are charges calculated?
- How are EV charging sessions tracked?
- How are reservations handled?

---

## 🚀 Use Cases

- Comic-Con event parking
- Stadium event parking
- Exhibition venue parking
- Multi-level mall parking
- Smart parking management system

---

## 📝 Notes

This design follows:
- Normalized structure
- Clear entity separation
- Reusable parking sessions
- Scalable multi-event architecture

---

**Feedback welcome to improve relationships and structure.**