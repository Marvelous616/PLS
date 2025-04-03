**Context for Website Flowchart**

### **Overview**
The flowchart represents the user journey for "G-Park," a parking lot management system. It details how different types of users (Students, Faculty, and Security) interact with the system through a login process and access different functionalities based on their roles.

### **User Types and Flow**
1. **Landing Page (G-Park)**
   - Displays an introduction to the application.
   - Contains a button labeled "Login to continue."
   
2. **Role Selection**
   - Users are prompted to select their role:
     - Student
     - Faculty
     - Security
   
3. **Login Process**
   - Each role has a dedicated login page with:
     - Registration number input
     - Password input
     - Options for "Forgot password" and "Login with OTP."

4. **Dashboard (Map Interface)**
   - **Students & Faculty:**
     - Can view a map and select parking lots.
     - Options to "Book a LOT" or "Unlock a LOT."
   - **Security:**
     - Can view a map with administrative privileges.
     - Options to "Change LOT details" and "Report on users."

### **Key Functionalities**
- **Authentication System:** Users must log in before accessing the map.
- **Role-Based Access:** Different users have different permissions.
- **Map Interface:** Central to the application, enabling parking lot management.
- **Administrative Features:** Security personnel can modify lot details and report users.

### **Next Steps**
- Implement the front-end design based on the flowchart.
- Integrate authentication and authorization.
- Develop interactive SVG or Canvas-based map for parking lot selection.
- Set up a backend to handle booking, unlocking, and reporting functionalities.
