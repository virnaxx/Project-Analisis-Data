# Proyek Analisis Data: E-commerce Public Dataset
- **Nama:** Virna Dalira Br Sebayang 
- **Email:** virnadalira@gmail.com
- **ID Dicoding:** pearnads

## Menentukan Pertanyaan Bisnis
1. Bagaimana Performa penjualan dan revenue perusahaan dalam beberapa bulan terakhir?
2. Produk apa yang paling banyak dan paling sedikit terjual ?
3. RFM ANALYSIS

## Import Semua Packages/Library yang Digunakan
- Kaggle installation
- Dataset download
- Libraries import

## Data Wrangling
### Gathering Data
1. Load `customers` table
2. Load `orders` table
3. Load `products` table
4. Load `order_items` table
5. Load `order_payments` table
6. Load `order_reviews` table
7. Load `sellers` table
8. Load `geolocation` table
9. Load `Category Name Translation` table

### Assessing Data
- Check data types and missing values
- Handle duplicates

### Cleaning Data
1. Remove duplicates
2. Handle missing values in `order_reviews`
3. Handle missing values in `orders`

## Exploratory Data Analysis (EDA)
### Explore data customers
- Customer demographics by city and state

### Explore data orders
- Calculate delivery time for each order
- Analyze order statistics

### Explore data orders and customers
- Identify active and non-active customers
- Merge orders and customers data

### Explore categories and revenue
- Analyze top-selling product categories
- Analyze revenue by city

## Visualization & Explanatory Analysis
### Sales and Revenue Performance Over the Last Months
- Line plot for monthly order count
- Line plot for total revenue

### Best and Worst Performing Products
- Bar plot for best and worst-performing products

### RFM Analysis
- Bar plots for Recency, Frequency, and Monetary parameters

## Conclusion
- Question 1: The company experienced the highest number of orders and revenue in November 2017, followed by a significant decline in December 2017.
- Question 2: The top-selling product category is "Cama mesa banho," while the least-selling product is "Mandarin Seguros e servicos."
- Question 3: RFM analysis identifies the best customers based on Recency, Frequency, and Monetary parameters.
