# Performance Testing using JMeter

This repository contains performance tests executed using JMeter to simulate various load conditions and assess the performance of different web services.

## Test 1: Aliexpress Performance Test

- **Test Description**: Simulates 5 virtual users making GET requests to the Aliexpress homepage.
- **Goal**: Evaluate the response time and server behavior under load.
- **Test Plan**:
  - 5 virtual users (threads)
  - Ramp-up time: 1 second
  - Each user performs 1 request
  - **HTTP Request**: GET https://aliexpress.com
  - **Assertion**: Response code 200 is expected for each request
  - **Other Elements**: Cookie Manager, Cache Manager, Results Collector

![image](https://github.com/user-attachments/assets/7996bc11-86dc-4681-8a51-95e3b896f393)
