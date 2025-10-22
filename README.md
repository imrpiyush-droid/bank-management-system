# 🏦 Bank Management System (Python)

### Overview  
Created a **Python-based Bank Management System** that allows users to **create, manage, and update customer bank accounts** using file-based storage.  
The application uses the **`pickle` module** for data serialization and supports multiple banking operations through a **menu-driven console interface**.

---

### 🔧 Features  

- **Create New Account**  
  Allows users to open new bank accounts by entering account number, name, account type, and initial balance.  

- **Deposit & Withdraw Amounts**  
  Enables secure money transactions — users can deposit or withdraw funds with validation for sufficient balance.  

- **Balance Enquiry**  
  Quickly check the current account balance by entering an account number.  

- **Modify Account**  
  Update existing account details such as holder name, account type, or balance.  

- **Close/Delete Account**  
  Remove an account permanently from the system records.  

- **View All Accounts**  
  Display a complete list of all account holders and their details.  

- **Data Persistence**  
  Account data is stored locally using **binary serialization (pickle)** in a file named `accounts.data`.  

---

### 💻 Technologies Used  
- **Programming Language:** Python  
- **Modules:**  
  - `pickle` — for object serialization  
  - `os` and `pathlib` — for file handling and data persistence  

---

### ⚙️ How It Works  

1. **Run the program**  
   ```bash
   python bank_management_system.py
   ```
2. The program will display an interactive menu in the console.  
3. Choose options (1–8) to perform various operations like creating an account, depositing, or checking balances.  
4. All data is saved automatically in `accounts.data`.  

---

### 📁 File Structure  

```
📂 BankManagementSystem
 ├── bank_management_system.py   # Main Python program
 ├── accounts.data                # Binary data file (auto-generated)
 └── README.md                    # Project documentation
```

---

### 🧩 Example Menu  

```
MAIN MENU
1. NEW ACCOUNT
2. DEPOSIT AMOUNT
3. WITHDRAW AMOUNT
4. BALANCE ENQUIRY
5. ALL ACCOUNT HOLDER LIST
6. CLOSE AN ACCOUNT
7. MODIFY AN ACCOUNT
8. EXIT
Select Your Option (1-8) :
```

---

### 🏁 Key Learning Outcomes  

- Implemented **object-oriented programming** using Python classes.  
- Gained practical experience with **file handling** and **binary serialization** using `pickle`.  
- Developed a functional **menu-driven application** for real-world scenarios.  

---

### 👨‍💻 Author  
**Piyush Kumar**  
*(Bank Management System – Python Console Application)*  
