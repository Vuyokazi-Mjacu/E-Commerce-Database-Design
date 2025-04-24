
# 🛍️ E-commerce Database Design

This project contains the structured SQL schema for a comprehensive e-commerce system. It covers products, brands, variations, attributes, inventory, and more — making it ideal for online retail platforms.

---

## 📁 Files Included

- `ecommerce.sql`: Contains all `CREATE TABLE` statements with relationships, primary/foreign keys, and constraints.

---

## 🧩 Entity Relationship Diagram (ERD)

The ERD showcases how tables like products, categories, variations, colors, and sizes are interlinked.

[ERD Diagram](Ecommerce databases.png) 

> Generated using [View ERD on Lucidchart](https://lucid.app/lucidchart/b4a385f3-a94a-447a-9102-b7a744540ddf/edit?view_items=gAW.t~0RQXyP&invitationId=inv_82171060-b64c-4468-8248-ed2a0601ac5e)  


---

## 🗂️ Database Tables Overview

| Table | Description |
|-------|-------------|
| `brand` | Stores brand names |
| `product_category` | Holds product category names |
| `product` | Central table with product details and foreign keys to brand and category |
| `product_image` | Stores product images and primary image flag |
| `color` | Reference table for product colors |
| `size_category` | Groups size options (e.g., Clothing, Shoes) |
| `size_option` | Available sizes (e.g., S, M, 42), linked to size category |
| `product_variation` | Each product's color/size combination |
| `product_item` | Final sellable item with price and stock |
| `attribute_type` | Type of attribute (Text, Number, Boolean, etc.) |
| `attribute_category` | Attribute grouping (e.g., Technical, Physical) |
| `product_attribute` | Key-value attributes for products |

---

## 🚀 How to Run

1. Open your MySQL Workbench or preferred SQL IDE
2. Create the database:

   ```sql
   CREATE DATABASE ecommerce_db;
   USE ecommerce_db;

## Group Members 
- Vuyokazi Mjacu
- Mercy Jepkosgei
- Philip Kyalo

