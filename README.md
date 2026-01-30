# Basic_POS_Project
Team Members

1. Aung Myat Oo Gyaw
2. Mi Hsu Myat Win Myint
3. Su Eain Dray Myint

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
Basic_POS_Project/
├── public/
│   └── pos_item.json          # Static product data (optional runtime fetch)
│
├── src/
│   ├── components/            # Reusable UI components
│   │   ├── AddProductForm.jsx # Form to add new products and categories
│   │   ├── SalesForm.jsx      # Form to record sales transactions
│   │   ├── SalesTable.jsx     # Table displaying sales records
│   │   └── Charts.jsx         # Recharts components (line & pie charts)
│   │
│   ├── pages/                 # Page-level components
│   │   ├── Dashboard.jsx      # Sales overview & analytics page
│   │   └── Journal.jsx        # Sales Journal (products & transactions)
│   │
│   ├── data/
│   │   └── productItems.js    # Initial product dataset
│   │
│   ├── utils/
│   │   └── storage.js         # LocalStorage helper functions
│   │
│   ├── styles.css             # Global application styles
│   ├── App.jsx                # Main app & routing
│   └── main.jsx               # Application entry point
│
├── Screenshots/               # Screenshots for README
│   ├── Dashboard.png
│   ├── SalesJournal.png
│   └── Charts.png
│
├── index.html                 # HTML entry file
├── package.json               # Project metadata & dependencies
├── vite.config.js             # Vite configuration
└── README.md                  # Project documentation

## Screenshot
Dashboard screenshot
![Dashboard Screenshot](images/dashboard1.png)
![Dashboard Screenshot](images/dashboard2.png)
SaleJournal Screenshot
![SaleJournal Screenshot](images/salejournal1.png)
![SaleJournal Screenshot](images/salejournal2.png)
![SaleJournal Screenshot](images/salejournal3.png)
