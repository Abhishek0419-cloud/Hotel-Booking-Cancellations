# Hotel Booking Cancellation Analysis

## 1. Business Problem

Hotels face significant revenue loss due to booking cancellations. High cancellation rates also make room planning and staff allocation difficult.
The goal of this project is to identify the factors responsible for cancellations and suggest actions to reduce them.

---

## 2. Dataset

* Source: Public hotel booking dataset (2015–2017)
* Records: 100,000+ bookings
* Key Columns: hotel type, lead time, arrival date, deposit type, customer type, cancellation status

---

## 3. Data Cleaning

* Removed duplicate records
* Handled missing values
* Converted date columns into usable format
* Standardized categorical values
* Checked outliers in booking lead time

---

## 4. Analysis Performed

* Exploratory Data Analysis (EDA)
* Cancellation rate comparison by hotel type
* Lead time vs cancellation relationship
* Customer type behavior analysis
* Seasonal trend analysis
* Visualization using Matplotlib / Power BI

---

## 5. Key Insights

* Bookings with long lead time had higher cancellation probability
* City hotels experienced more cancellations than resort hotels
* Customers without deposit were most likely to cancel
* Certain months showed peak cancellation rates

---

## 6. Business Recommendations

* Introduce partial advance payment for long lead-time bookings
* Offer discounts for non-refundable bookings
* Send reminder notifications before arrival dates
* Improve demand forecasting using seasonal trends

---

## 7. Tools Used

Python, Pandas, Matplotlib, Power BI
