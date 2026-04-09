## Bakery Buddy

Bakery Buddy is a full-stack inventory and production management system designed to replace a small business’s paper-based workflow with a digital solution. The system automates inventory tracking, recipe-based production, and sales reporting, allowing the business to focus on operations rather than manual bookkeeping.

---

### Problem Context
The client relied on handwritten logs to track:
- Ingredient usage  
- Product inventory  
- Sales and invoices  

This created inefficiencies, risk of errors, and limited visibility into business performance.

---

### Solution
We designed a system that:
- Automatically tracks ingredient inventory  
- Deducts stock based on recipes during production  
- Handles both online and offline sales (for market use)  
- Generates reports for business insights  
- Provides a simple, accessible UI tailored for non-technical users  

---

### My Contributions
As a backend developer, I was responsible for:
- Designing and implementing API endpoints  
- Defining functional and non-functional requirements  
- Contributing to system architecture and database design  
- Ensuring transactional integrity for inventory and sales operations  

---

### Technical Highlights

**Inventory Automation**
- Ingredients are automatically deducted when products are created or sold  
- Prevents inconsistencies between production and inventory  

**Offline Capability**
- Sales can be recorded without internet  
- Data synchronizes when connection is restored  

**Database Design**
- Fully normalized relational schema (3NF)  
- Designed to support scalability (products, recipes, sizes)  

![ERD](images/erd.png)

---

### Key Challenges
- Designing a system that supports both **offline and online workflows**  
- Ensuring **data consistency across multiple operations** (inventory, production, sales)  
- Creating a structure that remains **simple for end users but robust internally**  

---

### What I Learned
- How to design systems around real-world business constraints  
- The importance of transactional integrity in multi-step operations  
- How to translate client needs into technical requirements  
- Experience working in a team environment with defined roles  

---

### Why This Project Matters
This project demonstrates my ability to design and build systems that solve real business problems. It highlights my strengths in backend development, database design, and building reliable applications that balance complexity with usability.
