# Collection Analysis
The Head of Finance at "Bank X" wants to analyze the debt recovery efficiency of its partners. This analysis will help them decide on the allocation of the debt portfolio in the next quarter and determine an appropriate cooperation strategy. The goal is to ensure optimal debt recovery rates and maximize profits.

## I. Introduction
### 1. Introduction to Dataset
* Dataset: **OS Collection Performance**
* The dataset includes one table containing information on debt collection by partners, organized by month for the years 2020 and 2021.

### 2. Data Dictionary
<img width="868" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 12 38" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/87a55db9-057b-43fa-a86b-116085ce9ab7">

### 3. Business Questions
* Which Outsource companies are the most efficient at debt recovery, and what factors contribute to their success?
* How can the Head of Finance at Bank X optimize the allocation of the debt portfolio to maximize profits and minimize risk?
* What strategies can the Head of Collection at Bank X implement to improve debt recovery rates and enhance cooperation with its outsource companies?

## II. Design Thinking Method
### Step 1 - Empathize
<img width="1126" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 17 49" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/0f3946d7-6ed8-4d1f-bf79-124abd84cf28">

### Step 2 - Define
<img width="1129" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 19 39" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/a0137c20-6abe-4992-8ac8-97ee03178bdd">

### Step 3 - Ideate
<img width="940" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 20 33" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/9c2b022c-45f2-4ce9-bc77-ca59af7b4297">

### Step 4 - Prototype
<img width="938" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 21 23" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/9afeeab4-7c63-4acd-beed-01ccde0ebd4f">

### Step 5 - Review
<img width="940" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 21 53" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/9f269392-0a1b-427c-aa9d-c232b57fdf6d">

## III. Dashboard
### 1. Overview
<img width="807" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 45 02" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/6f5a7b62-e0fc-4eb3-ae63-a7bc1d9f9209">

### 2. Loan Profile
<img width="834" alt="Ảnh chụp Màn hình 2023-08-01 lúc 20 46 39" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/1e38d248-8e64-4075-b5db-f9d9240ac4fb">

### 3. Loan Recovery
<img width="838" alt="Ảnh chụp Màn hình 2023-08-01 lúc 21 04 12" src="https://github.com/nthao9987/Collection-Analysis/assets/80058129/3cbda955-1abc-4d0a-83d0-d09b25cbf9c6">


## IV. Insights
**1. In terms of total collection**
* ASA, HMK, GLX, NDC, TCG are the top companies with a lot of payment.
* BFC, FBI, TDO companies collect the least amount of loan.

**2. In terms of Loan terms**
* Mid-term: the companies with the highest total collection are: ASA> HMK>NDC>TCG>GLX
* Long-term: the companies with the highest total collection are: GLX>HMK>ASA>NDC>TCG
* Short-term: the companies with the highest total collection are: GLX>HMK>ASA>TCG>NDC
* Deadloan: the companies with the highest total collection are: NDC>FBI>GLX>ASA

**3. In terms of Recovery rate**
* The top companies with high revocery rates are: ASA>GLX>HMK.
* Unsecured loan is the most popular product (25.11%), but its recovery rate is lowest among companies.
* Secured loan has the lowest recovery rate despite its strict procedure.

4. Customers have a high demand for mid-term loans 37.79%, then short-term: 28.49%, long-term: 20.82%.

5. Credit card and Overdraft are popular (24.83% and 19.31%), but total PR is not high, perhaps because the customers of these 2 products are mainly individuals. -> The recovery rates of them are high.

6. Short-term is the easiest loan to claim (the highest recovery rate: 1.55%).

7. Deadloan has the highest amount of loan: Unsecured Loan, Secured Loan, Credit Card.

## V. Recommendations
**1. To collect a large amount of loan (total collected):**
Debt allocation according to loan term to OS_company
* Short-term: GLX, ASA, HMK
* Mid-term: ASA, GLX, NDC
* Long-term: ASA, HMK, NDC
* Deadloan: NDC

**2. For high recovery rate**
* Short-term: AMG, BFC, NDC
* Mid-term: NDC, GLX, ASA
* Long-term: NDC, TCG, ASA
* Deadloan: HMK

3. Consider whether the following companies should cooperate in the future because of the inefficient collection performance: FBI, TDO, BFC.
4. Expand and promote the Mid-term loan package because it has the highest recovery rate.
5. Investigate why secured loan has low recovery rate and take neccessary measures (review loan procedures, add requirements,etc.)
   







