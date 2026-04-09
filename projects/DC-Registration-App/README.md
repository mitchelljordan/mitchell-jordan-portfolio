## College Registration System – OOP Project

🔗 GitHub: https://github.com/mitchelljordan/DC_Registration_APP

### Overview
Desktop-based registration system built in C# using WPF, designed to manage student applications while demonstrating core object-oriented programming principles and maintainable code structure.

---

### Detailed Description

The College Registration System is a desktop application developed in C# (WPF) to simulate the end-to-end process of student admissions. The system handles applicant validation, program selection, eligibility filtering, and persistent data storage.

This project was primarily focused on applying and reinforcing the four core principles of object-oriented programming:

- **Inheritance** to model relationships between application entities  
- **Encapsulation** to control and validate access to sensitive data (e.g., student records)  
- **Polymorphism** to allow flexible handling of related object types  
- **Abstraction** to simplify complex validation and business logic  

---

### Key Features
- Student validation system (grades, test scores, eligibility filtering)
- Dynamic program selection based on location
- Admission management (create, update, delete records)
- File-based persistence using structured text/JSON
- UI-driven workflow with WPF (event-based architecture)

---

### Technical Implementation
- Built with **C# and WPF** using an event-driven architecture  
- Used **ObservableCollections** for real-time UI data binding  
- Implemented structured validation logic through class constructors and helper methods  
- Designed modular methods to separate UI logic from business rules  
- Managed persistent storage through file I/O and serialization  

---

### Challenges & Refactoring

A major challenge emerged during debugging due to overly complex, nested functions that made the system difficult to maintain and error-prone.

To resolve this, the codebase was refactored by:
- Breaking large methods into **single-responsibility functions**
- Reducing redundancy and improving readability
- Restructuring validation and control flow logic

This significantly improved:
- Debugging efficiency  
- Code maintainability  
- Overall system stability  

---

### Key Takeaways
- Poor structure compounds complexity—especially during debugging  
- Modular design is critical for maintainability  
- Refactoring is not optional—it’s part of the development process  
- Clean architecture matters as much as working code  

---

### Reflection

This project marked a turning point in how I approach software design. It shifted my focus from simply making code work to ensuring it is structured, maintainable, and scalable.

It also reinforced what I enjoy most about development: solving complex problems and iterating toward better solutions.

---

### Future Improvements
- Migrate from file storage to a relational database (e.g., PostgreSQL)
- Implement a layered architecture (UI / Service / Data)
- Add unit testing for validation logic
