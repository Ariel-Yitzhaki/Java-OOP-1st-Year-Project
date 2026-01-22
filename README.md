# Supermarket Management System

A console-based e-commerce simulation built in Java, demonstrating object-oriented programming principles.

## Features

- **User Management**: Register and manage buyers and sellers with authentication
- **Product Catalog**: Sellers can add products with categories, pricing, and optional gift wrapping
- **Shopping Cart**: Buyers can browse products, add items to cart, and checkout
- **Order History**: Track past purchases with date stamps and totals
- **Dynamic Data Structures**: Arrays that automatically resize as data grows

## Classes

| Class | Description |
|-------|-------------|
| `Main` | Entry point with menu-driven interface |
| `Buyers` | Manages buyer info, cart, and purchase history |
| `Sellers` | Manages seller info and product inventory |
| `Product` | Product details with category enum and wrapping option |
| `ShoppingCart` | Stores purchased items with date and total |
| `Address` | Buyer address information |

## How to Run

```bash
javac src/supermarket/*.java
java -cp src supermarket.Main
```

## Author

Ariel Yitzhaki
