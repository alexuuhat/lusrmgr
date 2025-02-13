# Windows User Management

**🚀 lusrmgr.exe:** If your Windows edition is not Enterprise or Pro, this tool allows you to modify and create user accounts.

## 📌 Overview
This repository provides essential commands and scripts for managing user accounts on Windows systems. It includes user creation, modification, deletion, and privilege management techniques.

## 🔥 Features
- ✅ Create and manage user accounts
- ✅ Modify user privileges
- ✅ Reset and change passwords
- ✅ Enable/disable user accounts
- ✅ List and manage group memberships

## 📂 Repository Structure
```
📁 win-user-management/
│── 📁 User-Creation
│── 📁 User-Modification
│── 📁 User-Deletion
│── 📁 Group-Management
│── 📁 Privilege-Management
```

## 🚀 Commands & Usage

### 1️⃣ Create a New User
```cmd
net user username password /add
```

### 2️⃣ Add User to Administrators Group
```cmd
net localgroup Administrators username /add
```

### 3️⃣ Remove a User
```cmd
net user username /delete
```

### 4️⃣ List All Users
```cmd
net user
```

### 5️⃣ Change User Password
```cmd
net user username newpassword
```

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/alexuuhat/win-user-management.git
   ```
2. Navigate to the directory:
   ```bash
   cd win-user-management
   ```
3. Use the provided scripts and commands as per your needs.

## 📜 Disclaimer
This repository is intended for educational and administrative purposes only. Use responsibly on authorized systems.

## ⭐ Contributions
Feel free to contribute by adding new scripts and improving existing ones!

## 📢 Connect with Me
- GitHub: [alexuuhat](https://github.com/alexuuhat)

🔹 **Star this repository if you find it useful!** ⭐
