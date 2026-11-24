# Prompt-Engineering-1
E-commerce Customer Query Classification

### Introduction: 
This project aims to make customer support easier by automatically classifying customer queries into different categories. It identifies what the customer needs help with, whether it's a delivery delay, payment issue, refund, cancellation, product defect, or account problem.
The goal is to save time, reduce manual work, and make handling customer queries more efficient.

### Prompt: 
I'll share customer queries from my e-commerce business. understand what the customer is asking and answer each query into one of these categories: Delivery Issue (order not received), Shipping if package stuck or delayed, Payment, Order Cancellation, Defective Product, Product Return, Account Issues, Refund, or Unknown if it doesn't fit any category. Just give me the category name without any explanation.

### Sample Inputs and Expected Outputs

| Sample Input | Expected Output |
|---|---|
| Where is my order? | Delivery Issue |
| My package is stuck. | Shipping |
| Payment failed. | Payment |
| Cancel my order. | Order Cancellation |
| Product arrived broken. | Defective Product |
| I want to return this item. | Product Return |
| I can't log in. | Account Issues |
| Where is my refund? | Refund |
| What is the weather today? | Unknown |

# Prompt-Engineering-2
E-commerce Customer Review Sentiment Analysis

### Introduction:
This project aims to help an online shopping company understand customer satisfaction by automatically analyzing customer reviews. It identifies whether a customer has a positive, negative, or neutral opinion about a product, service, or shopping experience.The goal is to save time, reduce manual analysis, and help the company understand customer feedback to improve product quality and customer service.

### Prompt:
based on customer reviews give me what kind of sentimental review has the company received from the customer according to this category: positive, negative, neutral (give outputs only according to the category without any explanation or additional text)

### Sample Inputs and Expected Outputs

| Sample Input | Expected Output |
|---|---|
| The product is excellent, and I love its quality. | Positive |
| The delivery was late, and the product was damaged. | Negative |
| The product arrived yesterday. | Neutral |
| The customer support team was extremely helpful. | Positive |
| The product is not worth the money. | Negative |
| The package contained two items. | Neutral |
| The phone is good, but the battery life is terrible. | Negative |

# Prompt-Engineering-3
Customer Query Urgency Classification

### Introduction:
This project aims to help a customer support company prioritize customer requests by automatically analyzing incoming queries. It identifies whether a customer's issue has High, Medium, or Low urgency based on its severity, impact, and time sensitivity. The goal is to reduce response delays, save time, and help support teams address critical customer issues efficiently while improving overall customer satisfaction.

### Prompt:
Analyze the customer query and classify its urgency as High, Medium, or Low based on severity, impact, and time. Return only one word without any explanation.

### Sample Inputs and Expected Outputs

| Sample Input | Expected Output |
|---|---|
| My bank account has been hacked, and money is being stolen. | High |
| My internet has been down for the entire day, affecting my work. | High |
| I haven't received my refund for the last seven days. | Medium |
| Can you tell me how to update my profile picture? | Low |
| I need to change my delivery address for an order arriving tomorrow. | Medium |
| I would like to know about your available subscription plans. | Low |
| I lost access to my account and cannot complete an urgent payment. | High |
