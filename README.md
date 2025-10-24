# API-Testing-with-JMeter
In this assignment, I created a complete API test plan in Apache JMeter using the public API https://api.restful-api.dev/objects . The test plan covered the full CRUD workflow (POST → GET → PATCH → DELETE → GET) with data-driven testing using a CSV file

# Test Plan Details
The JMeter Test Plan includes:
**POST** → Create new objects using data from a CSV file  
**GET** → Retrieve all and single objects  
**PATCH** → Update existing objects  
**Patch** → Update partially
**DELETE** → Remove objects  
**GET (After Delete)** → Validate deletion response  

# Key Learning
Built JMeter Test Plan using Thread Groups, Samplers & Listeners.
Automated complete CRUD API workflows.
Used CSV Data Set Config for POST requests.
