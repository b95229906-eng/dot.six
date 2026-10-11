# dot.six — Clothing & Everyday Style

Official open-source repository for **dot.six** ([_dot.six](https://www.instagram.com/_dot.six)), a minimalist black-and-white streetwear and everyday clothing e-commerce website.

## 🚀 Features

- **Minimalist Aesthetic:** Clean, monochrome Black & White design inspired by modern apparel brands like *Blur Village*.
- **Interactive Storefront (`index.html`):** 
  - Dynamic product catalog with category filters (T-Shirts, Hoodies & Sweatshirts, Bottoms).
  - Size selection (S, M, L, XL, etc.) and shopping bag slide-out drawer.
  - Simulated secure online UPI / Razorpay checkout flow.
- **Secret Admin Panel (`admin.html`):**
  - Manage inventory easily without touching code.
  - **Add, Edit, and Delete** products on the fly.
  - Persistent storage (`localStorage`) so your changes stay saved.
- **Responsive Design:** Fully optimized for mobile phones, tablets, and desktop displays.

---

## 🛠️ Project Structure

```text
├── index.html       # Main storefront page
├── admin.html       # Secret product management dashboard
├── style.css        # Global CSS styling (Black & white theme)
├── app.js           # Store logic, cart management, and CRUD admin logic
└── README.md        # Documentation
