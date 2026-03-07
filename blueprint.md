# 🚀 Application Blueprint

## 📱 App Name: BizNest

**Tagline:** “Your business, organized in one place.”

The idea is simple: a mobile command center for local business owners.

## 🎯 Target Users

Small local businesses such as:
*   retail shops
*   small restaurants
*   salons
*   repair services
*   freelancers

These businesses usually struggle with tracking money and customers.

## 🧩 Core Problem

Most small business owners:
*   don’t know daily profit
*   track sales in notebooks
*   forget customer details
*   have no analytics

BizNest becomes their digital business notebook.

## 📱 Core Features (Version 1)

1.  **Daily Sales Tracker**
    *   Owner enters: product or service, price, payment type
    *   The app automatically shows: daily, weekly, and monthly revenue

2.  **Expense Tracker**
    *   Track business expenses such as: supplies, rent, staff payments
    *   Then calculate actual profit.

3.  **Customer Manager**
    *   A simple CRM: customer name, phone number, purchase history, notes
    *   Later this can grow into marketing tools.

4.  **Business Dashboard**
    *   Home screen shows: today’s sales, expenses, profit, recent customers
    *   Simple charts.

5.  **Data Backup**
    *   Cloud sync using Firebase.
    *   So business data never gets lost.

## 🧱 Technical Blueprint

*   **Frontend:** Build the mobile app using Flutter.
    *   **Why?** One codebase for Android + iOS + Web.
*   **Backend:** Use a simple backend system such as Firebase.
    *   This handles: login system, cloud database, syncing data
*   **Database Structure:** Basic tables:
    *   `Users`
    *   `Business`
    *   `Sales`
    *   `Expenses`
    *   `Customers`

## 💰 Monetization

*   **Free plan:** basic sales tracking, limited data
*   **Premium plan ($5–$10/month):** advanced analytics, unlimited customers, data export

---

## Current Plan

### Initial Project Setup

*   [x] Create `blueprint.md`
*   [ ] Create a new Flutter project named "biznest".
*   [ ] Set up a feature-first project structure.
*   [ ] Integrate Firebase for backend services.
*   [ ] Create a basic UI for the main `Dashboard` screen.
