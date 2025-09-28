# Coffee-with-Polars
Data Analysis of a coffee shop using polars
# ☕ Bean There Coffee Shop Analysis with Polars

Welcome to the **Bean There Coffee Shop** data analysis project!  
This beginner-friendly project introduces **[Polars](https://pola-rs.github.io/polars/)**, a blazing-fast DataFrame library built in Rust, designed for speed, memory efficiency, and ease of use.  

We’ll simulate realistic coffee shop sales data and analyze it to uncover business insights — from best-selling drinks to customer behavior patterns.  

---

## Features

- Generate **fictional coffee shop data** (2,000 transactions).
- Explore **data schemas, sizes, and previews**.
- Add calculated columns like **total sales, day of week, month, and hour**.
- Perform **grouped analysis** (best sellers, daily revenue patterns).
- Identify **high-value transactions**.
- Understand **customer behavior and satisfaction trends**.
- Create a **business summary dashboard**.

---

## Installation

First, install the required packages:

```bash
pip install polars numpy
```
## Usage

Import the libraries:

```bash
import polars as pl
import numpy as np
from datetime import datetime, timedelta
```
---
## 📊 Workflow Overview

- **Generate Sample Data**
  - Create 2,000 transactions with columns like:
    - `date`
    - `drink`
    - `price`
    - `quantity`
    - `customer_type`
    - `payment_method`
    - `rating`

- **Enhance Data**
  - Add a `total_sale` column (revenue per transaction).
  - Extract date-based features: **day of week**, **month**, **hour of day**.

- **Analyze**
  - Find **best-selling drinks** (ranked by revenue, sold quantity, and rating).
  - Identify **daily business patterns** (revenue and transaction counts).
  - Filter **big orders** (transactions over \$10).
  - Analyze **customer behavior** (average spending, revenue, visit count, satisfaction).

- **Business Summary**
  - Output key metrics:
    - Total revenue
    - Total transactions
    - Average transaction value
    - Best-selling drink
    - Customer satisfaction score

**Best-Selling Drinks:**
| Drink      | Total Revenue | Total Sold | Avg Rating  |
|------------|---------------|------------|-------------|
| Americano  | 2242.0        | 595        | 3.47        |
| Mocha      | 2204.0        | 591        | 3.49        |
| Espresso   | 2119.5        | 570        | 3.51        |

---
## 🔗 Resources

- [Polars Documentation](https://pola-rs.github.io/polars/)
- [Numpy Documentation](https://numpy.org/doc/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)  <!-- optional -->
