# 🐾 StreetPawsTracker  
**A location-based street animal care and tracking system built with ASP.NET Core MVC and Leaflet.js.**

StreetPawsTracker enables users to track street animals’ feeding, water, and health status on an interactive map.  
The system aims to support community-driven animal care by allowing users to add animals, update their condition, and manage feeding/water points securely.

---

## 🚀 Features

### 🗺️ **Interactive Map (Leaflet.js)**
- Users can select locations by:
  - Using **current location**
  - Or **searching a location**
- A marker is automatically placed on the selected point
- Marker is draggable; latitude/longitude values update dynamically in the form

### 🐶 **Animal Management**
- Add animals with:
  - Photo
  - Description
  - Feeding status
  - Water status
  - Health condition
  - Neutering status
  - Notes
- Only the **user who added the animal** can delete it
- Other users can update status fields (feeding/water/health)

### 💧 Feeding & Water Points (Color-Coded System)

Feeding and water points are shown on the map using a clear color-coded marker system.  
Each color represents the current food and water status:

- 🔴 **Red:** Food empty, water empty  
- 🟢 **Green:** Food full, water full  
- 🟡 **Yellow:** Water empty, food full  
- 🔵 **Blue:** Food empty, water full  

Users can update each status independently (food available? / water available?).  
Markers update instantly on the map to reflect the latest changes, allowing the community to quickly identify which areas need attention.

### 🔐 **User Authentication (ASP.NET Identity)**
- Register / Login  
- Profile update  
- Access control for adding/editing animals  
- Identity-based ownership rules

### 🗂️ **CRUD Operations**
- All forms include server-side validation (DataAnnotations + ModelState)
- Dynamic forms inside map popups
- Real-time update feedback



