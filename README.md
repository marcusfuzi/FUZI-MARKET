# 🛒 FUZI MARKET
### Your Budget. Every Local Shop. One Smart Marketplace.

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=28&pause=1000&color=00C9A7&center=true&vCenter=true&width=750&lines=Welcome+to+FUZI+MARKET!;Discover+Local+Shops.;Compare+Prices+Instantly.;Find+the+Best+Deals+Near+You!;Shop+Smart.+Save+More." />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FUZI-MARKET-00C9A7?style=for-the-badge&logo=shopify&logoColor=white" />
  <img src="https://img.shields.io/badge/Project-Full%20Stack-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Web%20Application-blue?style=for-the-badge" />
</p>

<p align="center">
  <b>🚀 Bringing Local Shops and Smart Shopping Together!</b>
</p>

---

## 🌟 About FUZI MARKET

**FUZI MARKET** is a smart local shopping and price comparison marketplace that connects customers with nearby shopkeepers through a single digital platform.

The platform allows local shopkeepers to register their stores, upload products, manage prices, and showcase their inventory online.

Customers can search for products, set their preferred minimum and maximum budget, select a location radius, and discover the cheapest available options from registered local shops.

Instead of visiting multiple stores to compare prices, customers can find the best local deals from one place.

### 🎯 Our Vision

To transform traditional local shopping into a smarter, faster, and more transparent digital experience while helping local businesses grow.

---

## ✨ What Makes FUZI MARKET Special?

<p align="center">
  <img src="https://img.shields.io/badge/Smart-Price%20Comparison-00C9A7?style=flat-square" />
  <img src="https://img.shields.io/badge/Local-Shop%20Discovery-6366F1?style=flat-square" />
  <img src="https://img.shields.io/badge/Budget-Smart%20Search-F59E0B?style=flat-square" />
</p>

### 👤 Customer Dashboard

- 🔍 Search products by name, brand, and category.
- 💰 Set custom minimum and maximum price ranges.
- 📍 Discover nearby shops using location-based search.
- 📊 Compare prices across multiple local stores.
- 🏆 Automatically find the cheapest matching product.
- 📦 Check product stock availability.
- ⭐ View shop ratings and reviews.
- ❤️ Save favourite products.
- 📞 Contact shopkeepers through Call or WhatsApp.
- 🗺️ Get directions to nearby stores.

### 🏪 Shopkeeper Dashboard

- 📝 Separate shopkeeper registration and login.
- 🏬 Create and manage shop profiles.
- 📸 Upload product images and descriptions.
- 💵 Add and update product prices.
- 📦 Manage inventory and stock availability.
- ✏️ Edit and delete product listings.
- 📈 Monitor product views and customer interest.
- ✅ Get a verified shop badge after admin approval.

### 🛡️ Admin Dashboard

- 👥 Manage customers and shopkeepers.
- ✅ Approve or reject shop registrations.
- 🏬 Verify local businesses.
- 📋 Manage product listings.
- 🚫 Remove fake or misleading listings.
- 📊 Monitor platform statistics.
- ⚙️ Manage categories and reported content.

---

## 🧠 Smart Price Comparison Engine

The heart of FUZI MARKET is its intelligent product price comparison system.

Customers can search for a product and the application automatically finds matching products from registered shops within their selected budget and location.

### 💡 Example Scenario

A customer searches for Wireless Headphones.

**Selected Budget: ₹500 – ₹1,500**

| Local Shop | Product Price |
|---|---:|
| 🏆 Shop A | ₹699 |
| Shop B | ₹899 |
| Shop C | ₹1,199 |

<p align="center">
  <img src="https://img.shields.io/badge/BEST%20DEAL-₹699-00C9A7?style=for-the-badge" />
</p>

The cheapest matching product is displayed first.

**Comparison Logic:**
- Match the product brand, model, and variant.
- Apply the customer's budget filter.
- Filter shops according to location radius.
- Exclude unavailable products.
- Consider applicable delivery charges.
- Sort matching products by final payable price.

---

## 🎨 Modern UI / UX Experience

FUZI MARKET aims to deliver a premium and attractive shopping experience.

- ✨ Modern and responsive interface.
- 🎨 Premium color combinations.
- 🌈 Smooth animations and transitions.
- 💎 Glassmorphism-inspired components.
- 🛍️ Attractive product cards.
- 🔎 Interactive search bar.
- 🎚️ Dynamic budget range slider.
- 📱 Mobile-friendly dashboards.
- ⚡ Smooth loading animations.
- 🌙 Clean and modern layouts.

---

## ⚙️ Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,nodejs,express,mongodb,git,github,vscode" />
</p>

| Technology | Purpose |
|---|---|
| HTML5 | Frontend Structure |
| CSS3 | Styling and Animations |
| JavaScript | Frontend Functionality |
| Node.js | Backend Runtime |
| Express.js | REST API Development |
| MongoDB | Database |
| Mongoose | Database Modeling |
| JWT | Authentication |
| Bcrypt | Password Hashing |
| Cloudinary | Image Storage |
| Google Maps API | Location Services |

---

## 🏗️ Project Structure

```text
FUZI-MARKET/
│
├── frontend/
│   ├── index.html
│   ├── customer.html
│   ├── shopkeeper.html
│   ├── admin.html
│   │
│   ├── css/
│   │   ├── style.css
│   │   ├── dashboard.css
│   │   └── responsive.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   ├── auth.js
│   │   ├── customer.js
│   │   ├── shopkeeper.js
│   │   └── admin.js
│   │
│   └── assets/
│
└── backend/
    ├── config/
    ├── controllers/
    ├── middleware/
    ├── models/
    ├── routes/
    ├── server.js
    └── .env.example
```

---

## 🚀 Getting Started

Follow these steps to run FUZI MARKET locally.

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/fuzi-market.git
```

### 2. Open Project Folder

```bash
cd fuzi-market
```

### 3. Install Backend Dependencies

```bash
cd backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 5. Start Backend Server

```bash
npm run dev
```

### 6. Run Frontend

Open `frontend/index.html` using VS Code Live Server or another local development server.

---

## 🔐 Security Features

- Secure authentication using JWT.
- Password hashing using bcrypt.
- Role-based access control.
- Protected API endpoints.
- Input validation.
- Shop ownership verification.
- Admin-controlled shop verification.
- Environment-based secret management.

---

## 🔮 Future Enhancements

Our vision is to make FUZI MARKET even smarter with advanced features.

- 🤖 AI-powered product recommendations.
- 📉 Historical product price tracking.
- 🔔 Price drop notifications.
- 🛒 Online ordering and payment integration.
- 🚚 Delivery partner integration.
- 📍 Advanced location-based discovery.
- ⭐ Customer reviews and ratings.
- 📱 Dedicated Android and iOS applications.
- 🌐 Expansion across multiple cities.

---

## 💎 Why FUZI MARKET?

| Traditional Shopping | FUZI MARKET |
|---|---|
| Visit multiple shops | Compare shops digitally |
| Manually check prices | Automatic price comparison |
| Limited price awareness | Discover affordable options |
| Time-consuming process | Faster product discovery |
| Limited online visibility | Digital presence for local shops |

---

## 🤝 Contributing

Contributions and suggestions are always welcome!

1. Fork this repository.
2. Create a new feature branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Submit a Pull Request.

---

## 📌 Project Information

| Detail | Information |
|---|---|
| Project Name | FUZI MARKET |
| Project Type | Full Stack Web Application |
| Category | Local Shopping & Price Comparison |
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT |

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=23&pause=1000&color=00C9A7&center=true&vCenter=true&width=650&lines=Shop+Smart.+Compare+Better.;Save+More+With+FUZI+MARKET!" />
</p>

<h2 align="center">🛍️ FUZI MARKET</h2>

<h3 align="center">"Every Shop. Every Price. One Marketplace."</h3>

<p align="center">
  💚 Empowering Customers. Supporting Local Businesses.
</p>

<p align="center">
  ⭐ If you like FUZI MARKET, don't forget to star this repository!
</p>
