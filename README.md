# 🧾 PAN Number Validation Project (PostgreSQL)

## 📌 Objective
The goal of this project is to clean and validate a dataset containing Permanent Account Numbers (PAN) of Indian nationals, ensuring they follow the official format and are categorized as either **Valid** or **Invalid**.

---

## ⚙️ Data Cleaning & Preprocessing
- ✅ Handled **NULL values** (removed missing PANs)
- ✅ Removed **duplicates**
- ✅ Trimmed **leading & trailing spaces**
- ✅ Converted all PANs to **UPPERCASE**

---

## 📝 PAN Validation Rules
A valid PAN number must:
1. Be exactly **10 characters long**
2. Follow the format: **AAAAA1234A**
   - First 5 characters → Alphabets (A–Z), not sequential or repeating  
   - Next 4 characters → Digits (0–9), not sequential or repeating  
   - Last character → Alphabet (A-Z) 

**Examples**  
✔️ Valid → `AHGVE1276F`  
❌ Invalid → `ABCDE12345`, `AABCD1234Z`, `ABCDE1234`  

---

## 📊 Categorization
- **Valid PAN** → Matches the correct format  
- **Invalid PAN** → Incorrect format, incomplete, or non-alphanumeric  

---

## 📈 Summary Report
Generated a summary report with:
- Total records processed  
- Total valid PANs  
- Total invalid PANs  
- Total missing/incomplete PANs  

---

## 🛠️ Key SQL Concepts Used
- 🔹 **NULL handling functions**  
- 🔹 **UPPER() & TRIM()**  
- 🔹 **JOINS & CTEs**  
- 🔹 **User Defined Functions (UDFs)**  

---

## 📚 Learnings
Through this project, I gained hands-on experience with:
- Real-world **data cleaning and preprocessing** techniques  
- Applying **business rules in SQL** for validation  
- Writing efficient **PostgreSQL queries**  
- Structuring results into a professional **summary report**  

---

## Contact
**Somya Agrawal**  
- [LinkedIn](https://www.linkedin.com/in/somya-agrawal-analyst/)  
- [Portfolio](https://www.zapfolio.in/somya_agrawal936-bdark)  
- 📧 somya.agrawal936@gmail.com  

