# ER Diagram - SHOPEZ

## Overview
The ER diagram represents the structure of the database and shows how different entities like users, products, cart, and orders are connected in the ShopEZ e-commerce system.

---

## Entities

- **User**: Stores user details who use the platform.
- **Admin**: Manages banners and product categories.
- **Products**: Contains all available products.
- **Cart**: Stores products added by users (linked using userId).
- **Orders**: Stores all orders placed by users.

---

## Relationships

- A user can add multiple products to the cart.
- A user can place multiple orders.
- Each order contains multiple products.
- Products are managed by admin categories.

---

## Conclusion
The ER diagram clearly shows how users interact with products through cart and orders in the system.