## 🩸 Blood Bank Management System (PHP + MySQL)

### 📘 Overview

The **Blood Bank Management System** is a web-based application built using **PHP** and **MySQL** to manage and organize blood donations efficiently.
It helps **admins** manage donors, blood groups, and contact queries, while **donors/users** can register, search for blood groups, and make donation requests easily.

---

### 🧩 Project Modules

The system consists of **two main modules**:

1. **Admin Module**
2. **User (Donor) Module**

---

## 🧑‍💼 Admin Module
<img width="1920" height="888" alt="BBDMS-_-Admin-Dashboard" src="https://github.com/user-attachments/assets/75848ae4-1cde-43e3-a09d-5dac99f99e8d" />

### 🔹 Dashboard

* View total number of blood groups listed.
* View registered donor list.
* View total number of enquiries received.

### 🔹 Blood Group Management

* Add new blood group.
* Delete existing blood group.

### 🔹 Donor Management

* View a complete list of registered donors.
* Delete or hide donor details if required.

### 🔹 Manage Contact Queries

* View and manage user queries received from the **Contact Us** page.

### 🔹 Manage Pages

* Update website pages (e.g., About Us, Contact, etc.).

### 🔹 Update Contact Information

* Update the contact details displayed on the website.

### 🔹 Request Received by Donor

* View all the blood requests sent by donors.

### 🔹 Account Management

* Update profile.
* Change password.
* Recover password (Forgot password functionality).

---

## 🧍‍♂️ User (Donor) Module

### 🔹 Home
<img width="1920" height="4217" alt="Blood-Bank-Donar-Management-System-_-Home-Page" src="https://github.com/user-attachments/assets/b23f7f2c-cc60-4a62-a444-944cd2482893" />

* Welcome page for users and donors.
* Donors can register themselves to donate blood.

### 🔹 About Us

* View details about the organization or system.

### 🔹 Contact Us

* Send messages or queries to the admin.

### 🔹 Donor List
<img width="1920" height="1680" alt="BBDMS-_-Donor-List" src="https://github.com/user-attachments/assets/52897d2e-a68f-42e1-ae36-a4c55b56072f" />

* View the list of available donors with their contact details.

### 🔹 Search Donor

* Search donors by **city** and **blood group**.

---

## 🩸 Registered Donor Features (After Login)

### 🔹 My Account Section

* **Profile:** View and update personal details.
* **Change Password:** Update login password.
* **Request Received:** View blood requests sent by users.
* **Logout:** Securely sign out of the system.

---

### ⚙️ Technologies Used

| Component      | Technology                        |
| :------------- | :-------------------------------- |
| **Frontend**   | HTML, CSS, JavaScript, Bootstrap  |
| **Backend**    | Core PHP                          |
| **Database**   | MySQL                             |
| **Server**     | XAMPP / Apache                    |
| **IDE/Editor** | VS Code / Sublime Text / PHPStorm |

---

### 🗄️ Database Tables (Example)

| Table Name      | Description                                               |
| --------------- | --------------------------------------------------------- |
| `tbladmin`      | Stores admin login credentials and profile data.          |
| `tblbloodgroup` | Stores all available blood group types.                   |
| `tbldonor`      | Stores donor registration details.                        |
| `tblrequest`    | Stores requests made by donors.                           |
| `tblcontact`    | Stores contact queries from users.                        |
| `tblpages`      | Stores website page content (About Us, Contact Us, etc.). |

---

### 🧠 Key Features

✅ Secure Admin and Donor Login
✅ Add/Edit/Delete Blood Groups
✅ Donor Registration and Management
✅ Blood Request Management
✅ Search Donor by City and Blood Group
✅ Responsive Design using Bootstrap
✅ Password Recovery and Update Profile Features

---

### 📈 Future Enhancements

* Email notifications for blood requests.
* Integration of Google Maps for donor location tracking.
* SMS alerts for emergency blood requirements.
* Role-based access for hospital staff.

---
