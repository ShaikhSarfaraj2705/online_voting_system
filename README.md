# 🗳️ Online Voting System using PHP & MySQLi

## 📘 Overview
The **Online Voting System** is a web-based application developed using **PHP** and **MySQLi** that serves as an automated election platform for schools, colleges, or organizations.  
It simplifies the traditional manual voting process by allowing registered voters to cast their votes online, ensuring faster results and eliminating human error in vote counting.

The system provides two main interfaces:
1. **Administrator Panel**
2. **Voter Panel**

---

## 👨‍💼 Admin Module

### 🔹 Features
- **Manage Positions:** Add, update, delete, and reorder election positions displayed on the ballot.
- **Manage Candidates:** Add and manage all election candidates.
- **Manage Voters:** Create, edit, or delete voter accounts.
- **Vote Result Monitoring:** Automatically view and tally votes in real-time.
- **Result Visualization:** View results using **horizontal bar charts**.
- **Print Results:** Export and print election results in **PDF format**.
- **Vote Preview:** Allow admins to preview the voting interface.

---

## 🧑‍🗳️ Voter Module

### 🔹 Features
- **Secure Login:** Voters can log in using their credentials.
- **Vote Casting:** Choose and submit votes for preferred candidates.
- **Vote Preview:** Review votes before final submission.
- **Multiple Votes:** Supports elections with multiple voting categories or positions.
- **Instant Submission:** Once submitted, votes are locked to maintain election integrity.

---

## ⚙️ Technologies Used

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | PHP (MySQLi Extension) |
| **Database** | MySQL |
| **Server** | XAMPP / Apache |
| **IDE/Editor** | Visual Studio Code / Sublime Text |

---

## 🗄️ Database Tables (Example)
| Table Name | Description |
|-------------|--------------|
| `positions` | Stores all election positions (e.g., President, Secretary). |
| `candidates` | Stores candidate details and their assigned positions. |
| `voters` | Stores registered voters’ information and login credentials. |
| `votes` | Stores submitted votes per voter and candidate. |
| `admin` | Stores admin credentials and profile details. |

---

## 📊 Key Features Summary

✅ Vote preview before submission  
✅ Multiple votes per election cycle  
✅ Real-time vote tally using bar charts  
✅ Printable PDF results  
✅ Dynamic ordering of election positions  
✅ Full CRUD (Create, Read, Update, Delete) for voters, candidates, and positions  
✅ Secure authentication system for both admin and voters  

---

## 🧠 Future Enhancements
- Email or SMS notifications for election results  
- Two-factor authentication for voters  
- Blockchain-based vote verification  
- Mobile-friendly responsive interface  

---

## 🚀 How to Run the Project

1. **Download and Install XAMPP** on your system.
2. **Clone or download** this repository into your `htdocs` folder.
3. Import the provided **SQL file** into **phpMyAdmin** to create the database.
4. Update the database credentials in `config.php` file.
5. Start **Apache** and **MySQL** in XAMPP Control Panel.
6. Run the project in your browser


---

## 🏁 Conclusion
This **Online Voting System** provides a modern, fast, and secure solution for managing elections in organizations and institutions.  
By automating the voting process and result tallying, it ensures transparency, reduces manual effort, and enhances election integrity.

---

### 🖼️ Screenshot Preview

<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/d7e7846f-70bf-422e-97fa-3998777d8cb0" />

<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/39ddd72f-b362-42a3-9562-f4b8bdd2f550" />

<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/19ddf9d8-091d-40ca-86db-0b59777f3a14" />

<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/63017e3b-23ec-4730-bd0b-e4bb94b1ced3" />
