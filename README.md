# 🛍️ TypeShop — E-Commerce Cart System

A fully functional e-commerce shopping cart built with **pure HTML, CSS, and JavaScript**.  
No frameworks. No libraries. No build tools. Just clean vanilla code.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🌐 Live Demo

Simply open `index.html` in any browser — no server required!

---

## 📸 Features

### 🏪 Shop Page
- Browse 12 products across 5 categories
- Search products by name in real-time
- Filter by category (Electronics, Clothing, Books, Food, Sports)
- View product ratings, stock levels, and pricing
- Add items to cart with stock validation
- Visual feedback when item is already in cart

### 🛒 Cart Page
- View all items in cart with quantity controls
- Increase / decrease item quantity
- Remove individual items from cart
- Clear entire cart with one click
- Real-time price calculations (subtotal, tax, total)
- Persistent cart badge showing total items

### 🏷️ Discount System
- Apply coupon codes for discounts
- Percentage-based discounts (e.g., 10% off)
- Fixed-amount discounts (e.g., $20 off)
- Minimum purchase requirement validation
- Display available coupon codes as hints
- Remove applied discounts

### 💳 Checkout
- Complete order summary breakdown
- Animated success popup on checkout
- Random order number generation
- Itemized receipt in confirmation popup
- Estimated delivery info
- "Continue Shopping" flow after purchase

---

## 🎟️ Available Coupon Codes

| Code     | Type       | Value  | Min Purchase | Description                   |
|----------|------------|--------|--------------|-------------------------------|
| `SAVE10` | Percentage | 10%    | $50.00       | 10% off on orders above $50  |
| `FLAT20` | Fixed      | $20.00 | $100.00      | $20 off on orders above $100 |
| `MEGA25` | Percentage | 25%    | $200.00      | 25% off on orders above $200 |
| `FIRST5` | Fixed      | $5.00  | $0.00        | $5 off on any order          |

---

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- That's it! No Node.js, no npm, no installations needed.

### How to Run

```bash
# Option 1: Simply double-click
Just open index.html in your browser

# Option 2: Using VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click index.html → "Open with Live Server"

# Option 3: Using terminal
# Mac/Linux
open index.html

# Windows
start index.html

```
## 📁 Project Structure

ecommerce-cart/  
├── index.html          # Main HTML structure  
├── css/  
│   └── style.css       # All styles and animations  
├── js/  
│   ├── data.js         # Product data and discount codes  
│   ├── cart.js         # Cart logic (add, remove, discount, totals)  
│   ├── ui.js           # DOM manipulation and rendering  
│   └── app.js          # Main app initialization and event listeners  
├── assets/  
│   └── screenshots/    # Project screenshots (optional)  
└── README.md           # This file  

## 👨‍💻 Author

GitHub: @PoisonMunna
