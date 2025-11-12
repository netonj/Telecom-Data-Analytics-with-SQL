# Excelsior Mobile Customer Database Analysis

> This project analyzes a customer database to inform marketing efforts. 

---

## Project Overview

This project analyzed customer usage and billing data from the Excelsior Mobile database. By joining multiple tables containing subscriber information, device details, monthly usage, and billing amounts, SQL queries were used to identify trends in customer activity and revenue. The analysis compared average minutes, data usage, and bills across cities and plan types, and highlighted which customer segments generated the highest usage and revenue.

-**Objective:** To summarize and compare mobile usage patterns across customer demographics, plans, and devices in order to identify profitable and high-usage groups.
-**Domain:** Telecommunications
-**Key Techniques:** SQL data aggregation, relational joins, and comparative reporting.

---

## Data

-**Source**: BUAN 4210 WQ20 with Eric Lloyd at Seattle University.
-**Description:** 

There are 6 tables in the sample of Excelsior Mobile's DB:

Subscriber: Subscriber information including address, MDN and MIN.
Device: information about the devices used at Excelsior Mobile and has IMEI
DirNums: identifys the city and state of each MDN and connects it with an IMEI
MPlan: table of the plans used at Excelsior Mobile. Has data, throttle and cost
Bill: table of the current bills for each MIN, includes bill costs
LastMonthUsage: table of the last month of usage for each MIN, includes minutes, data in MB and texts

Variables used to join inlude:

MIN: Mobile Identification Number: unique number assigned by the wireless service provider. (account #)
MDN: The phone number
IMEI: International Mobile Equipment Identity: unique number for identifying a device on a mobile network. (like your vehicles VIN)

---

## Analysis

As this was a foundation Business Analytics course, this was a relatively modest analysis. All operations were compelted in SQL and Excel.

---

## Results

The analysis showed that Seattle and Olympia produced the highest total usage and revenue, with other Washington cities like Redmond and Everett following closely behind.

---

## Authors

- Jack Neton - [@netonj](https://github.com/netonj)
- 
---

## Acknowledgements

- BUAN 42100 at Seattle University taught by Eric Lloyd.
