<h1 align="center">📦 Inventory Management System</h1>

<p align="center">
A powerful <b>Java Console Application</b> to manage product inventory with stock operations and profit/loss tracking.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Language-Java-blue?style=for-the-badge&logo=java">
<img src="https://img.shields.io/badge/Platform-Console-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Data%20Structure-HashMap-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/OOP-Concepts-purple?style=for-the-badge">
<img src="https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=for-the-badge">
</p>

<p align="center">
<img src="https://cdn-icons-png.flaticon.com/512/263/263142.png" width="120">
<img src="https://cdn-icons-png.flaticon.com/512/1041/1041916.png" width="120">
<img src="https://cdn-icons-png.flaticon.com/512/2921/2921222.png" width="120">
</p>

---

## 🖥 Program Menu
```
Inventory Management System

1. List all products
2. Display individual product info
3. Purchase (add stock)
4. Shipping (sell stock)
5. Balance stock
6. Calculate loss and profit
7. Purchase report
8. Exit
```

---

## 🧠 System Architecture
```
          +----------------------+
          |        Main          |
          |   (User Interface)   |
          +----------+-----------+
                     |
             StockManager
                     |
            +--------v--------+
            |     Product     |
            |   Data Model    |
            +--------+--------+
                     |
              Inventory (HashMap)
```

---

## 🔄 Program Flow
```
Start
  |
  v
Display Menu
  |
  v
User Choice
  |
  +----> List Products
  |
  +----> View Product
  |
  +----> Purchase Stock
  |
  +----> Ship Product
  |
  +----> Update Stock
  |
  v
Calculate Profit/Loss
  |
  v
Exit
```

---

## 📂 Project Structure
```
inventory_management
│
├── Main.java
├── Product.java
├── StockManager.java
└── README.md
```

---

## 🧩 Core Classes

### 1️⃣ Product Class
Represents each product.

**Attributes**
- `productId`
- `productName`
- `price`
- `quantityInStock`

**Example**
```java
Product p = new Product("P001", "Laptop", 1200.00, 5);
System.out.println(p);
```

---

### 2️⃣ StockManager Class
Main controller of the application.

**Operations**
- Add Product  
- List Products  
- Purchase Stock  
- Ship Products  
- Update Stock  
- Calculate Profit/Loss  
- Generate Reports  

```java
Map<String, Product> inventory = new HashMap<>();
```

---

## 💾 Data Handling
- Inventory is managed using **HashMap**
- Tracks total revenue and expenses
- Calculates profit dynamically

---

## ⚙️ Installation & Running

### Compile
```bash
javac Main.java Product.java StockManager.java
```

### Run
```bash
java Main
```

---

## 🧪 Example Output
```
Enter Product ID: P001
Enter quantity to purchase: 5

5 units of Laptop purchased. New stock: 10
```

---

## 📊 Tech Stack

| Technology | Purpose |
|------------|--------|
| Java ☕ | Core programming |
| HashMap 🧠 | Data storage |
| Console 💻 | User interaction |

---

## 🔮 Future Improvements
🚀 MySQL Database  
🚀 Java Swing GUI  
🚀 Billing System  
🚀 Export Reports  
🚀 Web Version  

---

## 🤝 Contributing
- Fork the repo  
- Create a branch  
- Make changes  
- Submit PR  

---

## 👨‍💻 Author
**Mohammad Sahid**

---

## ⭐ Support
⭐ Star | 🍴 Fork | 📢 Share  

---

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=00FF00&center=true&vCenter=true&lines=Inventory+System+Project;Built+with+Java;Open+Source+Project">
</p>

<p align="center">
Made with ❤️ using Java
</p>
