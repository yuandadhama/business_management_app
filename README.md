# 📊 Console Business Management App (Java)

A simple **console-based business management application built with Java** designed to help small teams manage sales, stock, sellers, capital, revenue, and profit efficiently.

This project was inspired by a real experience when my friend and I ran a small snack business in our campus dormitory. While the business worked well, managing records manually through chat messages often caused missing data, calculation mistakes, and confusion when splitting money and tracking products. This application was created to solve those problems in a structured way.

---

## 🚀 Background

During my third semester in college, my friend and I sold snacks in our dormitory. We bought products from a store for around 5,000 IDR and resold them for 8,000 IDR, or 15,000 IDR if customers bought two. With shared capital and limited stock, each seller carried products separately.

Sales were usually reported through WhatsApp messages such as:

```
Andre 2  
Kevin 1  
```

However, problems often happened:

* Sellers sometimes forgot to report sales.
* Stock counting was done manually.
* Collected money didn’t match the number of sold products.
* Profit calculation became unclear.

From these small but real problems, this **Business Management App** was built using Java to make the process easier, cleaner, and more reliable.

---

## ✨ Features

* Create business records by date
* Track capital and stock
* Manage multiple sellers
* Record customer purchases
* Automatic revenue calculation
* Restocking system
* Seller performance tracking
* Simple file-based database

---

## 🗂 Application Flow

When the application starts:

```
1. Create New Field  
2. Show Existing Field  
```

### Create New Field

You will input:

* Capital
* Total product quantity
* Number of sellers
* Seller names

A database will be created like:

```
DB-1-2-2026
```

If the same date already exists:

```
DB-1-2-2026_(1)
DB-1-2-2026_(2)
```

---

### Dashboard

```
(1) Capital: 100.000  
(2) Quantity of Products: 20  
(3) Revenue: 0  
(4) Profit: 0  

== Options ==

(1) Add Customer  
(2) Restock  
(3) Info Seller  
(4) Back to Main Menu  
```

---

### Add Customer

Record customer purchases and seller activity:

```
== Packages ==
(1) Buy 1 product | 8k
(2) Buy 2 products | 15k

== Seller List ==
(1) Dhama
(2) Jonatan

Input Customer Name: Andreas
```

This will update stock, seller money, and revenue.

---

### Restock

Add more capital and products:

```
Input capital: 20000
Input product quantity: 4
```

---

### Info Seller

View seller details and money held:

```
1. Jonatan
   - package-one (0)
   - package-two (0)
Jonatan's Money: 0

2. Dhama
   - package-one (1): Andreas
   - package-two (0)
Dhama's Money: 8000

Total Money: 8000
```

---

## 🛠 Technologies

* Java
* Console Application
* File I/O
* Object-Oriented Programming

---

## 🎯 Purpose

This project is built to:

* Practice Java development
* Solve real business problems
* Reduce manual errors
* Improve seller coordination
* Learn data organization

---


## 👤 Author

**Yuanda Dhama Prandita**
