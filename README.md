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

## Test 2: BlogDeIT Performance Test  

- **Test Description**: Simulates 5 virtual users making GET requests to the BlogDeIT Free Stuff page.  
- **Goal**: Assess response time and server behavior under concurrent load.  
- **Test Plan**:  
  - 5 virtual users (threads)  
  - Ramp-up time: 1 second  
  - Each user performs 1 request  
  - **HTTP Request**: GET https://www.blogdeit.ro/free-stuff/  
  - **Other Elements**: Cookie Manager, Cache Manager, Results Collector  

![image](https://github.com/user-attachments/assets/b46841f9-7153-4790-ae23-96440290caed)

## Test 3: BlogDeIT Contact Page Performance Test

- **Test Description**: Simulates 5 virtual users making GET requests to the BlogDeIT contact page.
- **Goal**: Evaluate the response time and server behavior under load.
- **Test Plan**:
  - 5 virtual users (threads)
  - Ramp-up time: 1 second
  - Each user performs 1 request
  - **HTTP Request**: GET https://www.blogdeit.ro/contact/
  - **Assertion**: Response code 200 is expected for each request
  - **Other Elements**: Cookie Manager, Cache Manager, Results Collector

![image](https://github.com/user-attachments/assets/e01f9799-155b-4306-a3ee-e687fdb662b2)

## Test 4: BlogDeIT Home Page Performance Test

- **Test Description**: Simulates 10 virtual users making GET requests to the BlogDeIT home page.
- **Goal**: Evaluate the response time and server behavior under moderate load.
- **Test Plan**:
  - 10 virtual users (threads)
  - Ramp-up time: 1 second
  - Each user performs 1 request
- **HTTP Request**: GET https://blogdeit.ro
- **Assertion**: Response code 200 is expected for each request
- **Other Elements**: Cookie Manager, Cache Manager, Results Collector (View Results Tree, Summary Report)

![image](https://github.com/user-attachments/assets/56e32970-0f85-4643-8633-a264669a7bf0)

## Test 5: ChuckNorris API Performance Test

- **Test Description**: Simulates 5 virtual users making GET requests to the ChuckNorris API to retrieve a random joke from the "sport" category.
- **Goal**: Evaluate the response time and server behavior under load for the ChuckNorris API.
- **Test Plan**:
  - 5 virtual users (threads)
  - Ramp-up time: 1 second
  - Each user performs 1 request
- **HTTP Request**: GET https://api.chucknorris.io/jokes/random?category=sport
- **Assertion**: Response code 200 is expected for each request
- **Other Elements**: Cookie Manager, Cache Manager, Results Collector (View Results Tree, Summary Report)

![image](https://github.com/user-attachments/assets/9804ae67-f9cc-4ce9-b9fb-84592db42d16)
