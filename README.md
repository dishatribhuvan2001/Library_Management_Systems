# 📚 Library Management System  

## 📌 Overview  
The **Library Management System** is a web-based application developed using **ASP.NET, C#, ADO.NET, and SQL Server**. This system provides an efficient way to manage library operations, including book management, user management, book issuance, and fine calculations.  

## 🎯 Features  

### 🔐 Authentication & User Management  
- **User Registration** – New users can register using basic details.  
- **Login System** – Secure login with authentication.  
- **Reset Password** – Allows users to recover their accounts if they forget their credentials.  
- **Logout** – Securely log out from the system.  

### 🏠 Home Dashboard  
- Displays the **latest registered users** in a **GridView**.  
- Shows important **library statistics**, including:  
  - 📚 **Total Books** available in the library.  
  - 👥 **Total Users** registered in the system.  
  - ✅ **Active Users** currently using the library services.  
  - 💰 **Total Fine Collected** from overdue book returns.  

### 👤 User Profile  
- Displays user details, including **name, email, contact, and profile picture **.  
- Option to **update profile information**.  
- Shows a list of books issued to the user.  

### 📖 View Books  
- Allows users to **search books** using filters such as:  
  - **Book Title**  
  - **Author Name**  
  - **Category**  
- Displays **all books** in a **GridView** with details such as:  
  - Book Title, Author, Category, Availability Status  
- Users can **check availability** before issuing a book.  

### 📚 Manage Books (Admin/Librarian)  
Admin and Librarian can:  
- **Add New Books** – Enter book details, including:  
  - Title, Author, ISBN, Category, Quantity  
- **Update Books** – Modify book details such as title, quantity, or category.  
- **Delete Books** – Remove books from the system if they are no longer available.  
- **View All Books** – Display books in a **GridView** for easy management.  

### 📋 Book Issuance System  
- **Issue Books** to students in **two sections**:  
  1. **Student Details**  
     - Enter **Student ID** or search for a student.  
     - Display student details such as **Name, Contact, Membership Status**.  
  2. **Book Details**  
     - Select or search for a book.  
     - Display book details such as **Title, Author, Availability**.  
     - **Confirm Issuance** – Complete the process and assign a due date for return.  

### 📋 All Issued Books (Admin/Librarian)  
- View **all issued book details** in a **GridView**.  
- Displays:  
  - **Student Name**, **Book Title**, **Issue Date**, **Return Date**, **Fine**.  
- **Delete Issued Record** – Allows librarians to remove an issued book entry if required.  

### 💰 Fine Management System  
This feature helps in **tracking and collecting late return fines**.  
- **Fine Calculation**  
  - The system automatically calculates the **fine amount** if a book is returned after the due date.  
  - The fine rate can be predefined in the system settings.  
- **Pending Fine Details**  
  - Displays all **pending fines** in a **GridView** with:  
    - **User Name**  
    - **Book Title**  
    - **Due Date**  
    - **Fine Amount**  
    - **Payment Status** (Paid/Pending)  
- **Mark Fine as Paid**  
  - Librarians can update the status of a fine once payment is received.  

### 🔓 Logout & Security  
- Users can securely **log out** of their accounts to protect data.  
- **Role-Based Access Control** ensures only **admins and librarians** can access book management and fine-related features.  

---

## 🛠️ Technologies Used  

| **Technology**  | **Purpose** |
|---------------|------------|
| **ASP.NET WebForms/MVC** | Frontend & Backend |
| **C#** | Backend Programming |
| **ADO.NET** | Database Connectivity |
| **SQL Server** | Database Management |
| **Bootstrap** | UI Styling |
| **JavaScript & jQuery** | Client-side Interactions |
| **ASP.NET Identity (if implemented)** | Authentication & Authorization |

---
