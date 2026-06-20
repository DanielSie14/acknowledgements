# Analysis of the Impact of Query Caching Implementation on Reducing Database Server Workload in E-Commerce Applications 🚀

# Project Overview
This repository contains datasets, source code, workload scenarios, and other resource this experiment used
The study evaluates the effectiveness of query caching mechanisms using Redis and Memcached compared to a baseline MySQL implementation.
The experiments were conducted using a Laravel-based REST API, MySQL database, Apache JMeter for workload generation, and Ubuntu Server for system deployment.

# Research Goals
- Analyze the impact of Redis and Memcached on database server workload.
- Compare cache performance against a baseline MySQL implementation.
- Evaluate system performance under different workload intensities.
- Measure several performance metrics such as CPU utilization, response time, throughput, and query counts.

# Experimental Steps
These are 3 endpoints that represent e-commerce characteristics :
1. Search ALL PRODUCTS         -> /api/products
2. Filtering through Category  -> /api/products/category/laptop
3. Search specific items       -> /api/products/search?q=iphone

For the Scenario we are using 3 types of concurrent users :
- 10 users  -> Low workload
- 50 usesr  -> Medium workload
- 100 users -> High workload


