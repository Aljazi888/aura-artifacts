<div align="center">

# 💎 Aura Artifacts

### E-Commerce Platform for Handcrafted Gemstone Jewelry

*Embrace your inner light — jewelry crafted with intention, infused with meaning.*

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## ✨ About

**Aura Artifacts** is a full-stack e-commerce platform for handcrafted gemstone jewelry — bracelets, earrings, necklaces, rings, anklets, pendants and sunglasses, each featuring genuine stones with spiritual meaning.

The platform pairs an elegant, immersive shopping experience with a complete admin dashboard for running the store, and lets customers design their own bracelet stone by stone.

> Developed as the Web Development Project at **Imam Abdulrahman Bin Faisal University**, College of Science and Humanities – Jubail, Computer Science Department (2026).



## 💫 Features

### 🛍️ Shopping Experience
- **Product catalog** with multiple images per product, categories and filtering
- **Real-time search** with an instant results dropdown
- **Custom bracelet builder** — choose gemstones and charms with a live preview and price
- **Shopping cart** with quantity controls and live totals
- **Secure checkout** with shipping details and card validation
- **Wishlist** saved per user, previewed from the navigation bar
- **Currency converter** — 150+ currencies via a live exchange-rate API

### 👤 User Accounts
- Registration and login with **bcrypt** password hashing
- **Remember Me** sessions (7-day secure tokens)
- Profile management and full **order history** with status tracking
- Forgot-password request flow

### 🛠️ Admin Dashboard
- Sales analytics: revenue, orders, customers and top categories
- Manage **products, orders, customers, messages and subscribers**
- Promote users to admin (with self-demotion protection)
- **Notifications center** for new orders, registrations, messages and low stock
- Password reset request handling

### 🎨 Design & Accessibility
- Fully **responsive** across desktop, tablet and mobile
- **Dark mode** on every page
- Dedicated **Accessibility**, **Size Guide**, **Gemstone Meanings** and **Help / FAQ** pages
- Contact form with **Google Maps** integration
- Newsletter subscription

---

## 🔐 Security

- Passwords hashed with **bcrypt**
- **Prepared statements** on every database query to prevent SQL injection
- **CSRF protection** on forms
- Session-based guards on all admin routes
- Client-side and server-side **form validation**

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3 (custom properties, media queries), Vanilla JavaScript |
| Backend | PHP (MySQLi, sessions) |
| Database | MySQL — InnoDB, utf8mb4, foreign-key constraints |
| APIs | open.er-api.com (exchange rates), Google Maps |

---

## 🗄️ Database

16 normalized tables, including:

`admin` · `customer` · `category` · `product` · `gemstone` · `charm` · `cart` · `cart_item` · `bracelet_preview` · `order` · `order_item` · `wishlist` · `contact_message` · `newsletter` · `password_reset_request` · `notification_read`

---

## 🚀 Getting Started

1. **Install** [XAMPP](https://www.apachefriends.org/) (Apache + MySQL + PHP).
2. **Clone** the repository into the `htdocs` folder:
   ```bash
   git clone https://github.com/Aljazi888/aura-artifacts.git
   ```
3. **Create the database** in phpMyAdmin and import `database.sql`.
4. **Configure** the environment: copy `.env.example` to `.env` and fill in your database credentials.
5. **Run** Apache and MySQL, then open `http://localhost/aura-artifacts`.

---

## 👩‍💻 Team — Group 4

| Name |
|---|
| Zahra Hussain Alabdulatif |
| Razan Alqahtani |
| Aljazi Eddah Alsaiari |
| Zainab Alkathim |
| Fatima Musleh Alomar |
| Maha Alharthi |
| Rehaf Awad Alotaibi |

**Supervised by:** Ms. Raja Alyafer & Ms. Reem Alshammari

---

<div align="center">

*Made with 💗 and a little bit of gemstone magic.*

</div>
