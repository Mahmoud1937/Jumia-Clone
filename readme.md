# 🛒 **Jumia Clone - E-Commerce Backend**

> A full-featured backend clone of [Jumia](https://www.jumia.com/), one of Africa’s leading e-commerce platforms.  
> Built with **Node.js**, **Express**, and **MongoDB**, this backend handles all core functionalities required for a scalable online marketplace.

---

## 🚀 **Features**

✅ **User Authentication** (Register, Login, JWT)  
✅ **Google OAuth Integration**  
✅ **Role-Based Access Control** (Admin, Vendor, Customer)  
✅ **Product Listings** with Categories & Subcategories  
✅ **Vendor Store Creation & Management**  
✅ **Shopping Cart & Checkout**  
✅ **Order Management** (CRUD + Status Tracking)  
✅ **Coupons and Discounts**  
✅ **Wishlist Functionality**  
✅ **Reviews and Ratings**  
✅ **Email Verification & OTP System**  
✅ **RESTful API Architecture**  
✅ **Clean and Scalable Project Structure**

---

## 🧱 **Tech Stack**

- 🖥️ **Backend**: Node.js, Express.js  
- 🛢️ **Database**: MongoDB with Mongoose ODM  
- 🔐 **Authentication**: JWT, Google OAuth  
- 📧 **Email Service**: Nodemailer  
- 🛠️ **Development Tools**: Postman, VSCode, MongoDB Compass

---

## 📁 **Folder Structure**

```bash
jumia-clone-backend/
├── config/             # DB and environment setup
├── controllers/        # All route controllers
├── middleware/         # Auth, Error handling, etc.
├── models/             # Mongoose schemas
├── routes/             # API route definitions
├── utils/              # Helper functions
├── validators/         # Input validation logic
├── app.js              # Express app setup
├── server.js           # Entry point
└── .env                # Environment variables
