## Cloud Kitchen – Capstone Project

Cloud Kitchen is a full-stack mobile application developed as a capstone project, focused on helping users reduce food waste and make better use of available ingredients by generating recipes based on their pantry contents.

---

### Overview

The application allows users to manage a digital pantry, track ingredient expiry dates, and discover recipes tailored to what they already have at home. By combining pantry data with rule-based recommendation logic and external recipe APIs, the system simplifies daily meal decisions while promoting efficient food usage.

The project was designed as a realistic MVP within a constrained timeline, prioritizing core functionality, usability, and maintainable architecture over unnecessary complexity.

---

### My Role – Frontend Developer

I was responsible for the design and implementation of the frontend using Flutter. My work focused on building a responsive, intuitive interface and ensuring reliable communication with backend services.

---

### Key Features
- Pantry management system (add, edit, delete ingredients)
- Expiry date tracking with visual alerts
- Recipe discovery based on available ingredients
- Dietary preference filtering (e.g., dairy-free, low sodium)
- Rule-based recommendation system prioritizing expiring items
- Local data persistence for offline functionality

---

### Technical Implementation

- Built with **Flutter (Dart)** for cross-platform mobile development  
- Integrated with a **Python backend** via REST-style APIs  
- Used **SQLite (local storage)** for offline pantry and user data  
- Consumed external APIs (e.g., MealDB) for recipe data  
- Implemented **asynchronous data handling** with proper loading and error states  
- Structured frontend using **modular, reusable components**  
- Applied service-based abstraction for API communication  

---

### Architecture Overview

- **Frontend:** Flutter (UI, state management, API integration)  
- **Backend:** Python (business logic, API endpoints)  
- **Database:**  
  - SQLite (local device storage)  
  - PostgreSQL (centralized data handling)  
- **External APIs:** Recipe and ingredient data sources  

The system follows a layered architecture, separating UI, business logic, and data handling to improve maintainability and scalability.

---

### Key Contributions

- Designed and implemented multiple core screens (pantry, recipes, preferences)  
- Built reusable UI components to ensure consistency and scalability  
- Integrated backend APIs and handled asynchronous data flows  
- Managed state for pantry data, selected ingredients, and recipe results  
- Implemented structured navigation and routing across user flows  
- Handled error states and edge cases for improved user experience  

---

### Challenges & Problem Solving

One of the main challenges was managing complex state across multiple screens, particularly when synchronizing pantry data with recipe results.

To address this, I:
- Structured state handling more deliberately across components  
- Separated API logic into service layers  
- Reduced tight coupling between UI and data handling  

Another challenge was working within strict MVP constraints. Many advanced features (e.g., OCR scanning, AI recommendations) had to be intentionally scoped out.

This required:
- Prioritizing core functionality  
- Designing systems that could be extended later without major refactoring  

---

### What I Learned

- How to structure a scalable frontend architecture in Flutter  
- Practical experience integrating and consuming real-world APIs  
- The importance of clear separation between UI, logic, and data layers  
- How to balance feature scope with project constraints  
- Effective collaboration in a team-based development environment  

---

### Reflection

This project represents my most complete application, taking a system from concept to implementation within real-world constraints.

It reinforced the importance of:
- Building for maintainability, not just functionality  
- Making intentional trade-offs during development  
- Designing systems that can evolve beyond their initial scope  

---

### Future Improvements
- Add barcode scanning and receipt OCR for automated pantry input  
- Introduce AI-based recipe optimization and substitution  
- Implement cloud-based user accounts and synchronization  
- Expand filtering and recommendation algorithms  
- Add full nutrition tracking and analytics  
