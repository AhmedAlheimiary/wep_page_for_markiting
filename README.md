# 🏛️ Turath Al-Shumoukh — تراث الشموخ

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**الموقع الرسمي لمحل تراث الشموخ — أبو عدنان الوصابي**

*Marketing website for Turath Al-Shumoukh — a traditional Yemeni heritage shop specializing in Janbiya daggers, leather belts, and heritage accessories in Ibb, Yemen*

</div>

---

## 📋 Overview

A modern, responsive marketing website for **تراث الشموخ (Turath Al-Shumoukh)** — a traditional Yemeni heritage shop owned by **أبو عدنان الوصابي** in **Ibb, Yemen**. The site showcases traditional Yemeni products including Janbiya daggers, leather belts, and heritage accessories, with full e-commerce capabilities through WhatsApp ordering and a Firebase-powered admin dashboard.

---

## ✨ Features

### 🛍️ Storefront
- 🏠 **Hero Section** — Animated floating shapes, decorative ornaments, call-to-action buttons
- 📖 **About Section** — Shop story with feature badges:
  - ✅ جودة عالية (High Quality)
  - ✅ صناعة يدوية (Handmade)
  - ✅ خامات أصلية (Original Materials)
  - ✅ شحن وتوصيل (Shipping & Delivery)
- 📦 **Product Catalog** — 6+ products in 3 categories with filter buttons
- 🔍 **Product Filters** — Browse by category:
  - 🗡️ جنابي (Janbiya Daggers)
  - 👔 أحزمة (Leather Belts)
  - 🏺 تراثيات (Heritage Items)
- 🏷️ **Product Badges** — مميز / نادرة / VIP / جديد
- 🔎 **Image Lightbox** — Zoom into product images
- 📱 **WhatsApp Ordering** — Direct ordering via WhatsApp

### 🔧 Admin Dashboard
- 🔒 **Secret Access** — 5 clicks on logo → password login
- ➕ **Add Products** — Create with image upload (Base64 → Firestore)
- ✏️ **Edit Products** — Update product details
- 🗑️ **Delete Products** — Remove from catalog
- 🏷️ **Badge Management** — Assign badges to products
- 👁️ **Show/Hide Products** — Toggle product visibility
- 🖼️ **Image Compression** — Automatic compression before storage
- 💾 **LocalStorage Fallback** — Works offline when Firebase is unavailable

### 🎨 Design
- 📱 **Responsive Design** — Mobile hamburger menu
- 🔄 **RTL Layout** — Full Arabic right-to-left support
- 🎨 **Modern Animations** — Floating shapes and decorative elements
- 💬 **Floating WhatsApp Button** — Always-visible contact button
- 🔍 **SEO Optimized** — Google site verification, meta tags, keywords

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Page structure & semantic markup |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript** | Storefront logic, filters, lightbox |
| **Firebase Firestore** | Product database & real-time sync |
| **Base64 Encoding** | Image storage in Firestore |
| **WhatsApp API** | Direct product ordering |

---

## 📁 Project Structure

```
wep_page_for_markiting/
├── index.html              # Main storefront (525 lines)
├── admin.html              # Full admin dashboard (33KB)
├── style.css               # Main styles (25KB)
├── admin.css               # Admin panel styles (11KB)
├── script.js               # Storefront logic, filters, lightbox (255 lines)
├── admin.js                # Admin CRUD, product management (461 lines)
├── firebase-config.js      # Firebase setup + CRUD functions (128 lines)
└── images/
    ├── logo.png            # Shop logo
    └── products/           # Product images
```

---

## 🗡️ Product Categories

| Category | Arabic | Description |
|----------|--------|-------------|
| **Janbiya** | جنابي | Traditional Yemeni ceremonial daggers |
| **Belts** | أحزمة | Handcrafted leather belts |
| **Heritage** | تراثيات | Traditional Yemeni accessories and items |

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AhmedAlheimiary/wep_page_for_markiting.git
   ```

2. **Open** `index.html` in your browser for the storefront

3. **Open** `admin.html` for the admin dashboard

4. **For Firebase features:**
   - Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
   - Update `firebase-config.js` with your credentials
   - Enable Firestore in your Firebase project

---

## 👨‍💻 Author

**Ahmed Alheimiary**

---

## 📄 License

This project is for educational and demonstration purposes.
