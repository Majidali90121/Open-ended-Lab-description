# Open Ended Lab code is in seprate repostry due to github size limit And also rrun code in VS Community 
- You can download the entire project from here 
[Download Project](http://github.com/Majidali90121/Open_Ended_Lab-Code/raw/main/main.rar)
# 💊 Pharmacy Management System

A **C++ Console Application** to manage **patients, medicines, pharmacists, salesmen, and admin operations**.  
This system provides **login-based roles**, medicine expiry checks, billing, and reporting — making pharmacy management efficient and reliable.  


---
## 🏆 Key Features

- 🔑 **Login Based System**  
  - Admin Login  
  - Pharmacist Login  
  - Salesman Login  

- ✅ **Validation System**  
  - Patient must be registered before medicine issue  
  - Expired medicines cannot be added to stock  

- 🗂️ **File Handling**  
  - Patient information stored in file  
  - Sales, Pharmacist, and Admin information stored in file  
  - Expired medicines stored in a separate file  
  - Printed bill saved in a file  
  - Wrong admin/salesman/pharmacist entries logged in file  
  - Password reset attempts stored in file  

- 👨‍⚕️ **Patient Management**  
  - Add Patient (Name, Age, Disease)  
  - Search Patient by Name  
  - Patient entry saved with timestamp  

- 💊 **Pharmacist Features**  
  - Write medicine for patient  
  - Enter number of medicines required  
  - Generate total bill automatically  

- 🧑‍💼 **Salesman Features**  
  - Add Medicine (ID, Manufacturer, Category)  
  - Delete Medicine (updates stock automatically)  
  - Check expiry date before adding  
  - Search Medicine by ID  
  - Sell Medicines  
  - Generate Invoice  
  - Save expired medicine details in separate file  

- 📊 **Tracking & Reports**  
  - Work tracking: How much work done by Admin, Pharmacist, and Salesman in a day  
  - Sales report  
  - Yearly medicine entry report  

- 💵 **Payment System**  
  - Payment via **Cash, Bank, Easypaisa, JazzCash (Customizable)**  
  - Invoice generated after payment  



---

## 🖼️ Main Page
![Main Page](./Images/1.png)  
👉 This is the entry page of the system. It provides 3 options:  
- 👨‍💻 **Admin Page**  
- 💊 **Pharmacist Page**  
- 🧑‍💼 **Salesman Page**  
Also includes **Admin login**.

---

## 👨‍⚕️ Admin Panel
![Admin](./Images/2.png)  
👉 The Admin manages patients and overall system activities.  

Features:  
- ➕ **Add Patient** – Enter patient details like Name, Age, Disease  
- 🔍 **Search Patient** – Find patient records by name  
  ![Search Patient](./Images/3.png)  
- 🔑 **Reset Password** – Admin can reset password (changes are stored in file)  
  ![Reset Password](./Images/29.png)  
- 🛑 **Wrong Entry Log** – Invalid actions are saved into a file for tracking  
  ![Wrong Entry](./Images/28.png)  
- 📊 **Daily Work Report** – Track admin activities in one place  
    

---

## 💊 Pharmacist Panel
![Pharmacist](./Images/4.png)  
👉 Pharmacist manages **medicine prescriptions for patients**.  

Features:  
- 🔑 **Login System** – Pharmacist must log in to access system  
- 💡 **Medicine Request** – Enter number of medicines required for patient  
- 📝 **Medicine Details** – Enter medicine names → System returns name + price  
  ![Medicine Bill](./Images/5.png)  
- 💰 **Final Bill** – Automatic calculation of total cost  

---

## 🧑‍💼 Salesman Panel
![Salesman](./Images/6.png)  
👉 Salesman handles **medicine stock, sales, and billing**.  

Features:  
- ➕ **Add Medicine**  
- 📄 **View Medicine Details** – See expiry status & available stock  
  ![Medicine Details](./Images/7.png)  
- 🏷️ **Add Medicine Info** – Enter ID, Manufacturer, Category  
  ![Add Medicine](./Images/8.png)  
- ⛔ **Expired Medicine Check** – System blocks expired medicines  
  ![Expired](./Images/9.png)  
- 📆 **Yearly Medicine Report** – Shows total medicines entered in a year  
  ![Yearly Report](./Images/10.png)  
- 📦 **Medicine Stock Update** – Valid medicines added to stock  
  ![Stock](./Images/11.png)  
- 🗑️ **Delete Medicine by ID** – Auto-updates stock after deletion  
  ![Delete](./Images/12.png)  
  ![Deleted Stock](./Images/13.png)  
- 🔎 **Search Medicine by ID**  
  ![Search](./Images/14.png)  
- 💳 **Payment Process** – Handle payment for purchased medicines  
  ![Payment](./Images/15.png)  
- 🧾 **Invoice Generation** – Auto-generated after payment  
  ![Invoice](./Images/16.png)  
- 🗂️ **Expired Medicines File** – Wrongly added expired medicines are stored in a separate file  
  ![Expired File](./Images/17.png)  
- 🖨️ **Printed Bill** – Bill is saved into a file for records  
  ![Printed Bill](./Images/24.png)  

---

## 🧑‍🤝‍🧑 Patient Management
👉 All patient data is managed securely within the system.  

- 📋 **All Patients Stored** – Maintain patient records in the database  
  ![Patients](./Images/18.png)  
- ⏰ **Timestamp** – Patient entry stored with exact time  
  ![Patient Time](./Images/21.png)  
- 🔒 **Validation** – If a patient is not registered, medicines cannot be issued  
  ![Validation](./Images/23.png)  

---

## 📊 Reports
👉 The system generates reports for medicines, sales, and activities.  

- 📦 **Total Medicines Added**  
  ![Medicines Added](./Images/20.png)  
- 💹 **Sales Report**  
  ![Sales Report](./Images/22.png)  

---

## ⚙️ Technologies Used
- 🖥️ **Language:** C++  
- 📂 **Concepts:** File Handling, OOP, 

---

## Group 11
## 👨‍⚕️ Aurthor

- Abddul Majid Ali                   2024-SE-22
- Zulkarnain Mohid-Ud-Din            2024-SE-07
- Alishba Zakir                      2024-SE-02     

 
## Contributors
- [Majidali90121](https://github.com/Majidali90121) 🚀
- [CodeZulqarnain](https://github.com/CodeZulqarnain)💯
- [alishbazakir123](https://github.com/alishbazakir123) 🌟