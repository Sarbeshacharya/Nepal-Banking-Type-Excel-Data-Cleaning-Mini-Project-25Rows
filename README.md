# Nepal Banking Type Excel Data Cleaning Mini Project (25 Rows)

**Cleaned raw core-banking type data using Excel Text Functions making it ready for further analysis.**

---

## Project Overview
I took 25 rows of messy Nepal banking type customer data and turned it into a clean, professional dataset.

---

## What I Did
- Started with completely dirty data with extra spaces, broken dates, junk contact number, inconsistent balances,etc
- Applied full Excel Text Functions pipeline
- Created 3 sheets: Dirty Data → Cleaning Process → Final Clean Data

**Functions Used:**
-✅ TRIM + CLEAN → removed every hidden junk  
-✅ PROPER → perfect customer names  
-✅ SUBSTITUTE (nested monster) → fixed phones (+977, -, spaces)  
-✅ LEN + IF → validation with “review- Incomplete number” flag  
-✅ LEFT / RIGHT / MID → RBI-style masking (123456XXXX)  
-✅ DATEVALUE + TEXT + IF(ISNUMBER) → all dates now perfect DD/MM/YYYY  
-✅ VALUE + TEXT → clean numeric balances + ₹ formatted

---

## Screenshots

**1. Dirty Data**  
![Dirty Data](screenshots/1-dirty-data.png)

**2. Cleaning Process**  
![Cleaning Process](screenshots/2-cleaning-process.png)

**3. Final Clean Data**  
![Final Clean Data](screenshots/3-final-clean-data.png)

## Files in This Repo
- `datacleaningp.xlsx` – Complete file with all 3 sheets
- `screenshots/` – Before, During, and After visuals  
---

## What I Learned
- Banking data is always messy
- Text functions are the foundation of any data pipeline
- Validation + masking is critical for RBI/NRB compliance
---

## Let's Connect
Email: sarbeshacharya45@gmail.com  
LinkedIn: https://www.linkedin.com/in/sarbesh-acharya-93a3251b4?utm_source=share_via&utm_content=profile&utm_medium=member_ios


Dataset inspired by real Nepal Rastra Bank style exports.
