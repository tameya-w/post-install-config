# osTicket: Post-Installation Configuration

## Overview
This guide outlines the **Post-Installation Configuration** of **osTicket** after successful installation. The following configurations will enhance the ticketing system, manage users, and ensure a smooth help desk workflow.

## 🔗 Access Links
- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

![Screenshot 2025-03-18 092808](https://github.com/user-attachments/assets/1f2f7f74-4c66-482f-b8d9-7a67ca1ebd3d)

- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

![Screenshot 2025-03-18 091525](https://github.com/user-attachments/assets/505eace9-9ef0-4216-bd5b-7c13ef48f79f)

## 🎯 Key Configurations

### 1️⃣ Understanding Agent Panel vs Admin Panel
- **Agent Panel:** Used for handling tickets and interacting with customers.

![Screenshot 2025-03-18 093141](https://github.com/user-attachments/assets/c0ae7ac5-e820-4da3-890a-801e19695e9f)

- **Admin Panel:** Used for configuring settings, departments, teams, and system-wide features.

![Screenshot 2025-03-18 093013](https://github.com/user-attachments/assets/3d709bd5-0a39-4ea9-a286-9fbb04a1e836)

### 2️⃣ Configure Roles (For Grouping Permissions)
- **Path:** `Admin Panel → Agents → Roles`

![Screenshot 2025-03-18 093741](https://github.com/user-attachments/assets/4f65e4aa-283e-4efc-8007-a3f1ed0036c2)

- **Example Role:** `Supreme Admin` (Has full access to system configurations)

![Screenshot 2025-03-18 095344](https://github.com/user-attachments/assets/a489b5e4-2599-46d2-af6f-fdb80724a135)

![Screenshot 2025-03-18 095428](https://github.com/user-attachments/assets/6b8bd96a-65b4-475e-817e-3b54b74338a4)


### 3️⃣ Configure Departments (Ticket Visibility and Categorization)
- **Path:** `Admin Panel → Agents → Departments`

![Screenshot 2025-03-18 100100](https://github.com/user-attachments/assets/34bc76b5-7f03-4a80-9b17-e040a365b7c2)

![Screenshot 2025-03-18 100759](https://github.com/user-attachments/assets/4793786f-efc0-4a67-a254-393a6b83fd05)

- **Example Departments:**
  - `SysAdmins` (Handles system and infrastructure issues)
  - `Networking` (Manages network-related concerns)

![Screenshot 2025-03-18 100738](https://github.com/user-attachments/assets/f84aee2b-5bc5-44f1-9c34-40398150279c)


### 4️⃣ Configure Teams (Cross-Department Collaboration)
- **Path:** `Admin Panel → Agents → Teams`

![Screenshot 2025-03-18 101233](https://github.com/user-attachments/assets/926e8e59-f342-4c47-9a35-a05d2bb6ecf9)

- **Example Team:** `Online Banking` (Composed of agents from different departments to handle online banking issues)

![Screenshot 2025-03-18 101647](https://github.com/user-attachments/assets/d34b6ba3-56f0-4aae-95f8-3700d8f80244)

### 5️⃣ Adjust User Ticket Submission Settings
- **Path:** `Admin Panel → Settings → User Settings`
- **Allow Anyone to Create Tickets?** ❌ *(Uncheck this option to allow users to create tickets without logging in)*
- **Enable Registration Requirement:** ✅ *(Users must log in to submit tickets)*

![Screenshot 2025-03-18 102033](https://github.com/user-attachments/assets/76ada915-51e1-4228-b778-70172045cc51)

### 6️⃣ Configure Agents (Workers Handling Tickets)
- **Path:** `Admin Panel → Agents → Add New`

![Screenshot 2025-03-18 103147](https://github.com/user-attachments/assets/23f929de-2fbf-4c1a-8a5e-d8af49073b91)

- **Example Agents:**
  - `Jane (Department: SysAdmins)`
  - `John (Department: Support)`
![Screenshot 2025-03-18 103927](https://github.com/user-attachments/assets/18003e4c-afbc-4ffb-9880-2d21dbb288d2)

### 7️⃣ Configure Users (Customers Submitting Tickets)
- **Path:** `Agent Panel → Users → Add New`
- **Example User:**
  - `Karen`

![Screenshot 2025-03-18 115119](https://github.com/user-attachments/assets/f041d1d4-f6d5-431e-8f9f-69644364bf40)

### 8️⃣ Configure Service Level Agreements (SLA)
- **Path:** `Admin Panel → Manage → SLA`

![Screenshot 2025-03-18 122841](https://github.com/user-attachments/assets/f6f08a49-dec6-4480-998f-3987c5ac048e)

- **Example SLAs:**
  - `Sev-A (Grace Period: 1 hour, Schedule: 24/7)`
  - `Sev-B (Grace Period: 4 hours, Schedule: 24/7)`
  - `Sev-C (Grace Period: 8 hours, Business Hours)`

![Screenshot 2025-03-18 124958](https://github.com/user-attachments/assets/788361dd-22f6-48bc-92ec-e84193cc9f41)


### 9️⃣ Configure Help Topics (Categorizing User Ticket Requests)
- **Path:** `Admin Panel → Manage → Help Topics`

![Screenshot 2025-03-18 125416](https://github.com/user-attachments/assets/d5be1144-fb00-4245-b675-3b5d15aa6d5d)

- **Example Help Topics:**
  - `Business Critical Outage`
  - `Personal Computer Issues`
  - `Equipment Request`
  - `Password Reset`
  - `Other`

![Screenshot 2025-03-18 125902](https://github.com/user-attachments/assets/c025e4f6-605d-4742-82d1-14347346c82b)


## ✅ Conclusion
With these configurations in place, osTicket is now optimized for efficient ticket management. Agents can be assigned specific roles, departments, and teams to streamline ticket handling. Users must register before submitting tickets, ensuring a structured workflow.
