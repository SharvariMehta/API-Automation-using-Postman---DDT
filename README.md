# 🔍 Google Search DDT with Postman

This repository demonstrates **Data Driven Testing (DDT)** in Postman using the **Google Search API**.  
The test runs a search for numbers **1 to 10** dynamically using a JSON data file.

---

## 📂 Project Structure
```
📦 Google-Search-DDT

┣ 📜 DDT using POSTMAN.postman_collection.json   # Postman collection
┣ 📜 data.json                                   # Test data file (numbers 1–10)
┣ 📜 README.md                                   # Project documentation
````
---

## 📝 Test Case

**Test Case ID:** `TC_Google_Search_001`     
**Title:** Validate Google search results for numbers 1–10 using DDT in Postman

**Precondition:**

* Postman installed
* JSON file prepared with numbers 1–10

**Test Steps:**

1. Send `GET https://www.google.com/search?q={{number}}`
2. Iterate through values `1–10` using the data file
3. Validate response status code
4. Log searched number in test results
5. Verify response contains searched number

**Expected Result:**

* Each request returns **200 OK**
* Test results show which number was searched
---

## 📊 Sample Output (Runner)

```
✓ Searched number: 1
✓ Status code is 200
```
---
## 🙋‍♀️ Let’s Connect 👩‍💻

- 📧 **Email:** [sharvarimehta97@gmail.com](mailto:sharvarimehta97@gmail.com)  
- 💼 **LinkedIn:** [linkedin.com/in/sharvarimehta](https://www.linkedin.com/in/sharvarimehta)  
- 🚀 **GitHub:** [github.com/SharvariMehta](https://github.com/SharvariMehta)  
- 🔗 **Postman:** [postman.com/sharvarimehta](https://www.postman.com/sharvarimehta)  
---
