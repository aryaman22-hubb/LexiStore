# LexiStore

# 📚 Library Management System in C++  

A comprehensive **console-based Library Management System** built using C++ to efficiently manage book inventory, user records, and borrowing activities.  

This system allows librarians to:  
- Manage book inventory (Add, View, Edit, Delete)  
- Issue and return books to users  
- Maintain user records (Add, View, Edit, Delete)  
- Sort and search books for better organization  

---

## 🎯 Features  

- **Book Inventory Management:**  
  - Add new books with details (Title, Author, ISBN, Quantity)  
  - View all books with current stock status  
  - Edit book details (Title, Author, Quantity)  
  - Delete books from inventory  

- **User Records Management:**  
  - Add new users with Name and User ID  
  - View all registered users with borrowed books list  
  - Edit user details  
  - Delete user records  

- **Issue & Return Books:**  
  - Issue books to users and update inventory  
  - Return books and update stock  
  - Track which user has borrowed which book  

- **Sorting & Searching:**  
  - Sort books by Title or Author  
  - Search for books or users by name or ID  

---

## ⚙️ Installation & Compilation  

### Prerequisites  
- **C++ Compiler** (e.g., `g++`)  
- **Compatible Terminal** (Supports ANSI colors)  

### Compilation  
```bash
g++ library_management.cpp -o library
