# E-Commerce Website

A -responsive sample e-commerce website built using **HTML**, **CSS**, and **Vanilla JavaScript**, interacting with a mock API for dynamic data loading and cart functionality.

## 🔧 Features

- Product listing with categories
- Product detail view
- Add to cart functionality using `document.cookie`
- Dynamic cart with total price calculation
- Order placement and simulated API interaction

## 🛠️ Technologies Used

- HTML5, CSS3
- JavaScript (ES6+)
- [Mock API](https://5d76bf96515d1a0014085cf9.mockapi.io/product)
- XMLHttpRequest for API calls

## 📁 Folder Structure

```
project/
│
├── cart.html
├── cart.js
├── content.js
├── contentDetails.js
├── orderPlaced.js
├── css/
│   └── cart.css           # Styling for cart page
├── header.html            # Common header (loaded dynamically)
├── footer.html            # Common footer (loaded dynamically)
└── README.md
```

## ▶️ How to Run the Project

1. **Clone or Download** the repository to your local machine.

2. **Ensure a live server is used**:
   - Use the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code
   - Or use Python's built-in server:
     ```bash
     python3 -m http.server
     ```

3. **Navigate to `index.html`** (not included here but assumed), or directly open `cart.html` to view cart functionalities.

> ⚠️ Cookies are used to simulate cart state. Clear cookies or use incognito to reset cart.

## 🔗 API Reference

- `GET https://5d76bf96515d1a0014085cf9.mockapi.io/product` – fetch product list
- `GET https://5d76bf96515d1a0014085cf9.mockapi.io/product/:id` – fetch specific product
- `POST https://5d76bf96515d1a0014085cf9.mockapi.io/order` – simulate order placement

## 📷 Screenshots

### Home Page
![Home](https://user-images.githubusercontent.com/17312616/65086776-b1beb080-d9d0-11e9-9983-143d61ed8fdc.png)

### Product Description
![Description](https://user-images.githubusercontent.com/17312616/65086777-b1beb080-d9d0-11e9-9e2b-af3b7210bdf3.png)

### Cart Page
![Cart](https://user-images.githubusercontent.com/17312616/65086778-b2574700-d9d0-11e9-9377-8e4886f582a8.png)

### Order Confirmation
![Order](https://user-images.githubusercontent.com/17312616/65086779-b2efdd80-d9d0-11e9-95d5-4b1a48eafe04.png)
