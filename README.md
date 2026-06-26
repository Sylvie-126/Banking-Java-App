Database Person (Franklin) → Owns the data layer, ensures persistence, and connects everyone’s work. This is essential because the database is the backbone of the banking app.

Login & Signup Person (Nelly) → Handles authentication and account creation, which is the entry point for all users.

Dashboard & Profile Person (Ella) → Manages the main hub and user details, making the app feel personalized.

Deposit, Withdraw & Balance Person (Maya) → Covers the most frequently used banking operations, ensuring balances update correctly.

Fund Transfer Person (Precious) → Focuses on transfers, which are slightly more complex (validations, receipts, error handling).

Designer / Screen Builder (Ireoluwatomiwa) → Ensures all screens are visually consistent and connected, helping others integrate their logic smoothly.



---

## 📅 Timeline Plan (6 Days)

### **Day 1 – Setup & Skeletons**
- **Designer (Ireoluwatomiwa)**:  
  - Build all FXML skeletons (Login, Dashboard, Profile, Deposit, Withdraw, Transfer, History).  
  - Apply basic CSS for consistent look.  
- **Database (Franklin)**:  
  - Create schema (Users, Accounts, Transactions).  
  - Set up connection class (e.g., JDBC utility).  
- **Everyone else**:  
  - Pull the repo, set up environment, confirm they can run the skeleton app.

---

### **Day 2 – Core Pages**
- **Login/Signup (Nelly)**:  
  - Implement login logic (check credentials from DB).  
  - Implement signup (insert new user into DB).  
- **Dashboard/Profile (Ella)**:  
  - Populate dashboard with user info after login.  
  - Build profile update + change password forms.  
- **Designer**:  
  - Wire navigation buttons (e.g., Dashboard → Deposit).

---

### **Day 3 – Banking Operations**
- **Deposit/Withdraw/Balance (Maya)**:  
  - Implement deposit (update balance in DB).  
  - Implement withdraw (check balance, deduct).  
  - Implement balance display.  
  - Start transaction history list.  
- **Fund Transfer (Precious)**:  
  - Implement transfer form (recipient account, amount).  
  - Validate sender balance, update both accounts.  
  - Generate receipt message.

---

### **Day 4 – Integration**
- **Database (Franklin)**:  
  - Test DB queries with Maya & Precious.  
  - Ensure transactions update correctly.  
- **Designer**:  
  - Refine navigation (Back buttons, Logout).  
  - Apply consistent styling across all pages.  
- **Everyone**:  
  - Start connecting their controllers to DB methods.

---

### **Day 5 – Testing & Debugging**
- **Tester role (shared among all)**:  
  - Run through flows: Login → Dashboard → Deposit → History → Logout.  
  - Check edge cases (wrong password, insufficient funds, invalid account number).  
- **Security (Nelly + Ella)**:  
  - Ensure password hashing or at least secure checks.  
  - Confirm logout clears session.

---

### **Day 6 – Final Polish**
- Fix any bugs found during testing.  
- Add small UI touches (hover effects, icons).  
- Prepare demo script: show login, deposit, transfer, history, logout.  
- Write short documentation (how to run, features, team roles).

---

## 👥 To‑Dos by Member

- **Franklin (DB)** → Schema, connection class, CRUD queries, integration testing.  
- **Nelly (Login/Signup)** → Login form, signup form, credential validation, session tracking.  
- **Ella (Dashboard/Profile)** → Dashboard info display, profile update, change password.  
- **Maya (Deposit/Withdraw/Balance)** → Deposit/withdraw logic, balance label, transaction history.  
- **Precious (Transfer)** → Transfer form, validation, receipt generation.  
- **Ireoluwatomiwa (Designer)** → Build all FXMLs, CSS styling, navigation wiring.

---
