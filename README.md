# Basic_POS_Project
Team Members
- **Aung Myat Oo Gyaw (6726066)**
  Github: [Kizut0](https://github.com/Kizut0)
- **Mi Hsu Myat Win Myint (6726115)**
  Github: [hsumyatwin-myint](https://github.com/hsumyatwin-myint)  
- **Su Eain Dray Myint (6726094)**
  Github: [u6726094-dot](https://github.com/u6726094-dot)  


## 📌 Project Description
- A **Web-based Point of Sale (POS) and Sales Analytics** application built using **React** and **Vite**
- Designed to help users **record sales transactions**, **manage products**, and **analyze sales performance**
- Consists of **two main pages**:
  - **Dashboard** – provides sales overview and visual analytics
  - **Sales Journal** – used to manage products and record sales transactions
- Dashboard features:
  - Total sales (all time)
  - Sales summary by period (Daily, Weekly, Monthly)
  - Sales trend visualization using a line chart
  - Sales distribution by category using a pie chart
  - Top 5 selling products
- Sales Journal features:
  - Add new products with category and unit price
  - Support for creating **new product categories** (duplicate categories are prevented)
  - Record sales by selecting product, quantity, and date
  - Automatically calculate total sale price
  - Display and manage transaction history in a sortable table
- Uses **LocalStorage** for data persistence
- Does **not use any backend server**
- Developed as part of a **University coursework assignment**

## 🛠️ Technology Stack
- React
- Vite
- Recharts
- LocalStorage

## 📁 Folder Structure
```
Basic_POS_Project/
├── public/
│   └── pos_item.json          # Static product data (optional)
│
├── src/
│   ├── components/            # Reusable UI components
│   │   ├── AddProductForm.jsx # Add new products and categories
│   │   ├── SalesForm.jsx      # Record sales transactions
│   │   ├── SalesTable.jsx     # Sales history table
│   │   └── Charts.jsx         # Line & Pie charts (Recharts)
│   │
│   ├── pages/                 # Application pages
│   │   ├── Dashboard.jsx      # Sales dashboard & analytics
│   │   └── Journal.jsx        # Sales journal page
│   │
│   ├── data/
│   │   └── productItems.js    # Initial product data
│   │
│   ├── utils/
│   │   └── storage.js         # LocalStorage helpers
│   │
│   ├── styles.css             # Global styles
│   ├── App.jsx                # Routing & layout
│   └── main.jsx               # App entry point
│
├── Screenshots/               # README screenshots
│   ├── Dashboard.png
│   └── SalesJournal.png
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🧭 Instructions of Application Functions

## 📊 Dashboard Page
The Dashboard provides an overview of sales performance and analytics.

#### Users can:
- View total sales of all time
- View sales summary by period (Daily / Weekly / Monthly)
- Visualize sales trends using a line chart
- View sales distribution by category using a pie chart
- Display Top 5 best-selling products
- Dashboard is read-only (no data input)

#### Notes:
- All charts update automatically when new sales are recorded
- Dashboard data is read-only (no data input on this page)

![Dashboard Screenshot](images/dashboard1.png)
![Dashboard Screenshot](images/dashboard2.png)

## 🧾 Sales Journal Page
The Sales Journal is used to manage products and record sales transactions.

#### Users can:
- Add new products by entering:
  - Product name
  - Category (select existing or create new)
  - Unit price
- Prevent duplicate categories when creating new categories
- Record new sales by:
  - Selecting a product
  - Entering quantity
  - Selecting transaction date
- Automatically calculate total sale amount
- View all sales transactions in a table
- Delete individual sales records if needed


#### Notes:
- Product category in a sale is auto-filled and cannot be edited manually
- All data is stored in **LocalStorage**
- No backend server is used

![SaleJournal Screenshot](images/salejournal1.png)
![SaleJournal Screenshot](images/salejournal2.png)
![SaleJournal Screenshot](images/salejournal3.png)


