# Performance Testing with Apache JMeter

##  Project Overview
This project focuses on assessing the **performance, scalability, and reliability** of the [Swag Labs](https://www.saucedemo.com/) web application using **Apache JMeter**.  

The tests simulate real-world user scenarios (login, search, add to cart, checkout) under varying loads to evaluate:
- **Response Times**
- **Throughput**
- **Error Rates**
- **Scalability**

The ultimate goal is to identify performance bottlenecks and ensure the application meets the defined performance requirements.

---

## Objectives
- Validate responsiveness of critical user journeys.
- Ensure throughput of **≥ 500 requests per second** under peak load.
- Confirm error rate remains **≤ 1%** during execution.
- Evaluate system scalability and stability under load and endurance conditions.

---


## Test Scenarios
The following user flows are covered:

1. **User Login**
2. **Search Products / Browse Inventory**
3. **View Product Details**
4. **Add to Cart**
5. **Checkout Process**

---

## Performance Goals (SLAs)
- **Response Time:** ≤ 2s average; ≤ 3s at the 95th percentile.
- **Throughput:** ≥ 500 requests per second.
- **Error Rate:** ≤ 1% of total requests.
- **Scalability:** Application should scale linearly until peak load and degrade gracefully beyond.

---

##  Workload Model
- **Baseline Test:** 50 concurrent users
- **Load Test:** 150 concurrent users
- **Peak Test:** 300 concurrent users
- **Stress Test:** up to 500+ users
- **Endurance Test:** 300 users for over 2–4 hours

