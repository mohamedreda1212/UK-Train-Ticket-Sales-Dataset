# 🚆 UK Train Ticket Sales Dataset  
A detailed simulated dataset of UK National Rail ticket sales from **January → April 2024**.

---

# 📌 Overview  
The dataset contains comprehensive information about **train ticket sales**, including:

- Ticket type & class  
- Journey date & time  
- Departure & arrival stations  
- Ticket price & discounts  
- Delay & cancellation data  
- Refund request information  

This dataset enables deep analysis of **ticketing trends**, **passenger behavior**, and **railway performance**.

---

# 🎯 Objectives  
The dataset aims to:  

- ⏱️ Analyze delay times for journeys  
- 💸 Explore relation between purchase time & ticket price  
- ❌ Understand reasons for cancelled trips & reduce cancellations  
- ⚠️ Understand delay causes & link to refund requests  
- 🏙️ Improve performance of departure/arrival stations  
- 📈 Identify peak ticket purchasing hours  

---

# 📂 Data Source & Description  
The dataset originates from **UK Train Rides**, and includes around **31,653 ticket purchases** (Jan–Apr 2024).

### 📁 Included Tables  
#### **1) Railway Table**  
💳 Transaction & purchase details, ticket info, railcard info, payment method.

#### **2) Trips Table**  
🚉 Trip ID, stations, delay info, coordinates.

#### **3) Dim Journey Date**  
📅 Date, time, weekday type.

#### **4) Station Table**  
📍 Station name & coordinates.

#### **5) Ticket Details**  
🎟️ Ticket class, type, price.

#### **6) Purchase Information**  
🕒 Purchase date/time, purchase type, payment method, days before journey, purchase hour.

#### **7) Journey Details**  
🚆 Journey date, status, arrival times, delay minutes, reason for delay/cancellation.

---

# 🔑 Key Columns  
(Ready for GitHub)

| Column | Description |
|--------|-------------|
| **Transaction ID** | Unique ID for each ticket purchase. |
| **Date of Purchase** | Date the ticket was purchased. |
| **Time of Purchase** | Time the ticket was purchased. |
| **Purchase Type** | Online or Station. |
| **Payment Method** | Contactless, Credit Card, Debit Card. |
| **Railcard** | Adult, Senior, Disabled, None. Railcard gives 33% off. |
| **Ticket Class** | Standard / First. |
| **Ticket Type** | Advance (50% off), Off-Peak (25% off), Anytime (full price). |
| **Ticket Price** | Ticket cost. |
| **Departure Station** | Starting station. |
| **Arrival Destination** | Ending station. |
| **Journey Date** | Date of travel. |
| **Departure Time** | Scheduled departure time. |
| **Arrival Time** | Scheduled arrival time. |
| **Actual Arrival Time** | Real arrival time. |
| **Journey Status** | On Time / Delayed / Cancelled. |
| **Reason for Delay** | Cause of delay or cancellation. |
| **Refund Request** | Whether refund was requested. |
| **Origin-Destination** | Combined departure → arrival. |
| **Delay Time (minutes)** | Difference between scheduled and actual arrival. |
| **Merged Column** | Origin-destination + journey date + departure time. |
| **Purchase Hour** | Extracted hour from purchase time. |

---

# 📊 Data Analysis Questions  

## 🚦 Performance Analysis  
1. What % of total trips were cancelled or delayed?  
2. Which routes have the highest cancellations/delays?  
3. Is there a relationship between trip volume and cancellation rate?

## 💰 Revenue Analysis  
4. Which routes generate the most revenue?  
5. What is the revenue loss due to delays/cancellations?  
6. Are there monthly/seasonal trends in revenue or delays?

## 🛣️ Route Optimization  
7. Routes with low performance & low revenue → candidates for removal.  
8. Routes with poor performance but high revenue → essential routes.

## ⚙️ Operational Efficiency  
9. Which times/days have the highest delays?  
10. Average delay duration per route or ticket type.

## 📉 Comparative Analysis  
11. How do high-performing vs low-performing routes differ?  
12. Is trip performance improving or declining over time?
