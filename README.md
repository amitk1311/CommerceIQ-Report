# CommerceIQ-Report
A Python script to analyze e-commerce data and diagnose performance issues.


E-Commerce Diagnostic Script for CommerceIQ Assessment
This repository contains my solution for the CommerceIQ take-home assessment. I developed a Python script that analyzes e-commerce data to diagnose performance issues for a client experiencing revenue fluctuations despite increased ad spend.

Key Discoveries 💡
My script analyzed inventory, pricing, and advertising data to uncover several critical issues:

📉 Declining Ad Performance: The primary issue identified was a consistent 3-week drop in Return on Ad Spend (ROAS) for the top-selling product (NT-EARBUD-X1), falling from 4.76 to 2.75.

🛒 Lost Buy Box: Key products (NT-EARBUD-X1-BLK and NT-SPEAKER-Z2) were losing sales directly to third-party competitors who were undercutting them on price.

📦 Out of Stock: Critical products were found to be out of stock or running low, representing significant missed revenue opportunities.

Recommendations ✅
Based on these findings, I prioritized the following actions:

Immediately audit the NT-EARBUD-X1 ad campaigns to stop the declining ROAS.

Investigate competitor pricing for Buy Box losses and check for MAP policy violations.

Escalate inventory issues to the supply chain team to expedite replenishment.

Tech & Setup ⚙️
Language: Python
Libraries: Pandas, NumPy
To Run

Place the data files in the root directory.

Run the script from the scripts/ folder.

The final JSON report will be generated in the outputs/ folder.
